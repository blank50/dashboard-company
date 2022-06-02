<template>
     <div>
        
     <el-menu router :default-active="$router.path" class="el-menu-demo topnav"  mode="horizontal" active-text-color="white" background-color="#29304C"> 
      <v-list-item-avatar>
                     <img src="../assets/cloud.jpg">
              </v-list-item-avatar>
              中达进出口
              <el-menu-item index="1"><img src="../assets/computer.png"/>Daily Office</el-menu-item>
     <el-menu-item index="2"><img src="../assets/topsec.png"/>Job Functions</el-menu-item>
    <el-menu-item index="3"><img src="../assets/home.png"/>Personal Development</el-menu-item>
    <v-list-item-avatar >
                     <img src="../assets/4.png"/>
              </v-list-item-avatar>

                 <v-list-item-avatar>
                     <img src="../assets/question.png"/>
              </v-list-item-avatar>


                     <v-list-item-avatar>
                     <img src="../assets/nyasha.jpg"/>
              </v-list-item-avatar>
                    </el-menu>

                </div>
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


<style>
.column {
  display: flex !important;
  align-items: center !important;
}
.columns {
  margin-top: 0 !important;
}
.padding-right {
  padding-right: 15px;
}
.image {
  height: 10px;
  width: 10px;
}

</style>