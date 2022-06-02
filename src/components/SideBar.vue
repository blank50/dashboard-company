<template>
    <nav> 
        <div>
     <el-menu router :default-active="$router.path" class="el-menu-demo topnav"  mode="horizontal" active-text-color="white" background-color="#29304C"> 
    <el-menu-item index="1" class="ml-16"><img src="../assets/computer.png"/>Daily Office</el-menu-item>
     <el-menu-item index="2" class="ml-8"><img src="../assets/topsec.png"/>Job Functions</el-menu-item>
    <el-menu-item index="3" class="mr-16 ml-8"><img src="../assets/home.png"/>Personal Development</el-menu-item>
            
                    <v-list-item-avatar class="navbar-nav > li mx-16">
                     <img src="../assets/4.png"/>
                    </v-list-item-avatar>
                    <v-list-item-avatar class="ml-16">
                        <img src="../assets/question.png"/>
                    </v-list-item-avatar>
                        <v-list-item-avatar>
                        <img src="../assets/nyasha.jpg"/>
                    </v-list-item-avatar>
                    </el-menu>
                </div>
   
        <v-navigation-drawer v-model="drawer" dark app mini-variant mini-variant-width="180" color="#29304C" class="">
            <v-list-item-avatar  class="logotext">

      <img src="../assets/cloud.jpg">
            </v-list-item-avatar>
    <span class="logotext">中达进出口</span>
            <v-list-item-group align="center">
                <v-list>
                    <v-list-item router to="/">
                        <v-list-item-content>
                            <div class="link-container">
                                <i class="fas fa-home"></i>
                            </div>
                        </v-list-item-content>
                    </v-list-item>
                </v-list>
                <v-list>
                    <v-list-item router to="/todolist">
                        <v-list-item-content>
                            <div class="link-container">
                                <i class="fas fa-clipboard-list"></i>
                            </div>
                        </v-list-item-content>
                    </v-list-item>
                </v-list>
                <v-list>
                    <v-list-item router to='/calender'>
                        <v-list-item-content>
                                <div class="link-container">
                                    <i class="fas fa-calendar-alt"></i>
                                </div>
                        </v-list-item-content>
                    </v-list-item>
                </v-list>
                <v-list>
                    <v-list-item router to='/information'>
                        <v-list-item-content>
                                <div class="link-container">
                                    <i class="fas fa-chalkboard-teacher"></i>
                                </div>
                        </v-list-item-content>
                    </v-list-item>
                </v-list>
                <v-list>
                    <v-list-item router to='/message'>
                        <v-list-item-content>
                                <div class="link-container">
                                    <i class="fas fa-comment-dots"></i>
                                </div>
                        </v-list-item-content>
                    </v-list-item>
                </v-list>
                <v-list>
                    <v-list-item router to='/mytask'>
                        <v-list-item-content>
                                <div class="link-container"><i class="far fa-envelope-open"></i>
                                </div>
                        </v-list-item-content>
                    </v-list-item>
                </v-list>
                <v-list>
                    <v-list-item router to='/file'>
                        <v-list-item-content>
                                <div class="link-container">
                                    <i class="fas fa-file-alt"></i>
                                </div>
                        </v-list-item-content>
                    </v-list-item>
                </v-list>
                <v-list>
                    <v-list-item router to='/contacts'>
                        <v-list-item-content>
                                <div class="link-container">
                                    <i class="fas fa-address-book"></i>
                                </div>
                        </v-list-item-content>
                    </v-list-item>
                </v-list>
               
                
            </v-list-item-group>
        </v-navigation-drawer>
    </nav>

</template>
<script>

export default {
    data() {
        return {
        activeIndex: '1',
        activeIndex2: '1'
      };
    },
    methods: {
      handleSelect(key, keyPath) {
        console.log(key, keyPath);
      }
    }
}

</script>
<style scoped>
div >>> .v-list a {
    text-decoration: none;
}
.logotext{
    color: white;
}
.sidebar {
    color: white;
    background-color: var(--sidebar-bg-color);

    float: left;
    position: fixed;
    z-index: 1;
    top: 0;
    left: 0;
    bottom: 0;
    padding: 0.5em;

    transition: 0.3s ease;

    display: flex;
    flex-direction: column;
}
.side-btn {
    border: none;
    padding: 5px 0px;
    cursor: pointer;
    font-size: 16px;
    font-weight: 500;
    color: white;
    background-color: transparent;
}


.side-btn:focus {
    outline: none;
}

.side-btn.active {
    position: relative;
    background-color: #29304C;
    color: #29304C;
    margin-left: 5px;
    border-radius: 0px 0 0 0px;
}

.side-btn.active::before {
    top: 0px;
}

.side-btn.active::after {
    bottom: 0px;
}

.side-btn.active::before, .side-btn.active::after {
    position: absolute;
    content: "";
    right: 0;
    background-color: #29304C;
}

.side-btn.active .link-container::before {
    top: 0px;
}

.side-btn.active .link-container::after {
    bottom: 0px;
    z-index: 99;
}

.side-btn.active .link-container::before, .side-btn.active .link-container::after {
    position: absolute;
    content: "";
    right: 0px;
    height: 10px;
    width: 20px;
    border-radius: 30%;
    background-color: #29304C;
}
.title {
    color: white;
    font-size: 10px;
    margin-top: 50px;
   
   
}
.topnav{
    margin-left: 150px;
    

}
.navbar-nav > li{
  padding-left:30px;
  padding-right:30px;
}
.navbar-nav > li{
  margin-left:400px;
}

</style>