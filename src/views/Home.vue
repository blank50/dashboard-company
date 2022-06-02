<template>

  <v-app :style="{background: $vuetify.theme.themes.light.background}">
    <h1 class="headingings">Home</h1>
    <v-layout row>
      <v-flex md8>
        <v-app :style="{background: $vuetify.theme.themes.dark.background}" class="">

          
          <v-container>
              <v-row>
                <v-col cols="12" sm="6" >
                  <h3 class="headingings1 ml-3">My Task <el-button class="morebutton ml-16  my-3">More<i class="el-icon-arrow-right"></i></el-button></h3>
                    <v-card class="mx-3 rounded-tl-xl rounded-tr-xl rounded-bl-xl rounded-br-xl" color="red" text-color="white">
                      <v-list-item>
                        <v-list-item-content class="generalfont">
                          <v-list-item-title class="headline mb-1">
                          </v-list-item-title>
                          <v-card-text> <span class="white--text">
                            <span class="innertext">3点去总经理办公室取回签字文件。<v-list-item-avatar tile size="14" class="ml-16 ">
                            <img src="../assets/star.png"/>
                            </v-list-item-avatar></span>
                            
                            <br>
                            <v-list-item-avatar tile size="12" class="fortime">
                            <img src="../assets/time.png"/>
                            </v-list-item-avatar>
                            <span class="timedisplay ">2020-09-09 10:00am</span>
                            <v-list-item-avatar tile size="16" class="rounded-tl-xl rounded-tr-xl rounded-bl-xl rounded-br-xl ">
                              <img src="../assets/nyasha.jpg"/>
                            </v-list-item-avatar>
                            <v-divider/>
                            <span class="innertext">采购单报销。<v-list-item-avatar tile size="14" class=" ml-16">
                            <img src="../assets/lightning.png"/>
                            </v-list-item-avatar></span>
                            <br>
                            <v-list-item-avatar tile size="12" class="fortime">
                            <img src="../assets/time.png"/>
                            </v-list-item-avatar>
                            <span class="timedisplay ">2020-09-09 10:00am</span>
                            <v-list-item-avatar tile size="16" class="rounded-tl-xl rounded-tr-xl rounded-bl-xl rounded-br-xl">
                              <img src="../assets/nyasha.jpg"/>
                            </v-list-item-avatar>
                            <v-divider/>
                            <span class="innertext ">客户离开，以及帮客户预约车辆。<v-list-item-avatar tile size="14" class="ml-16">
                            <img src="../assets/star.png"/>
                            </v-list-item-avatar></span>
                            <br>
                            <v-list-item-avatar tile size="12" class="fortime">
                            <img src="../assets/time.png"/>
                            </v-list-item-avatar>
                            <span class="timedisplay ">2020-09-09 10:00am</span>
                            <v-list-item-avatar tile size="16" class="rounded-tl-xl rounded-tr-xl rounded-bl-xl rounded-br-xl">
                              <img src="../assets/nyasha.jpg"/>
                            </v-list-item-avatar>
                            </span>
                          </v-card-text>
                        </v-list-item-content>
                      </v-list-item>
                    </v-card>
                </v-col>
                <v-col cols="12" sm="6"  >
                  <h3 align="" class="ml-4">Intermediate task <el-button class="morebutton ml-16 my-3" align=right >More<i class="el-icon-arrow-right"></i></el-button></h3>
                    <v-card class="mx-3 rounded-tl-xl rounded-tr-xl rounded-bl-xl rounded-br-xl" color="orange">
                      <v-list-item>
                        <v-list-item-content class="generalfont">
                          <v-list-item-title class="headline mb-1">
                          </v-list-item-title>
                           <v-card-text> <span class="white--text">
                            Anytime we can inspire a smile in another, that's a good thing
                            <br>
                            <v-list-item-avatar tile size="12" class="fortime">
                            <img src="../assets/time.png"/>
                            </v-list-item-avatar>
                            <span class="timedisplay ">2020-09-09 10:00am</span>
                            <v-list-item-avatar tile size="16" class="rounded-tl-xl rounded-tr-xl rounded-bl-xl rounded-br-xl ml-2">
                              <img src="../assets/nyasha.jpg"/>
                            </v-list-item-avatar>
                            <v-list-item-avatar tile size="16" class="rounded-tl-xl rounded-tr-xl rounded-bl-xl rounded-br-xl ml-n1">
                              <img src="../assets/nyasha.jpg"/>
                            </v-list-item-avatar>
                            <v-list-item-avatar tile size="16" class="rounded-tl-xl rounded-tr-xl rounded-bl-xl rounded-br-xl ml-n1">
                              <img src="../assets/nyasha.jpg"/>
                            </v-list-item-avatar>
                            <v-divider/>
                            Anytime we can inspire a smile in another, that's a good thing
                            <br>
                            <v-list-item-avatar tile size="12" class="fortime">
                            <img src="../assets/time.png"/>
                            </v-list-item-avatar>
                            <span class="timedisplay ">2020-09-09 10:00am</span>
                            <v-list-item-avatar tile size="16" class="rounded-tl-xl rounded-tr-xl rounded-bl-xl rounded-br-xl ml-2">
                              <img src="../assets/nyasha.jpg"/>
                            </v-list-item-avatar>
                            <v-list-item-avatar tile size="16" class="rounded-tl-xl rounded-tr-xl rounded-bl-xl rounded-br-xl ml-n1">
                              <img src="../assets/nyasha.jpg"/>
                            </v-list-item-avatar>
                            <v-divider/>
                            Anytime we can inspire a smile in another, that's a good thing
                            <br>
                            <v-list-item-avatar tile size="12" class="fortime">
                            <img src="../assets/time.png"/>
                            </v-list-item-avatar>
                            <span class="timedisplay ">2020-09-09 10:00am</span>
                            <v-list-item-avatar tile size="16" class="rounded-tl-xl rounded-tr-xl rounded-bl-xl rounded-br-xl ml-2">
                              <img src="../assets/nyasha.jpg"/>
                            </v-list-item-avatar>
                            <v-list-item-avatar tile size="16" class="rounded-tl-xl rounded-tr-xl rounded-bl-xl rounded-br-xl ml-n1">
                              <img src="../assets/nyasha.jpg"/>
                            </v-list-item-avatar>
                            <v-list-item-avatar tile size="16" class="rounded-tl-xl rounded-tr-xl rounded-bl-xl rounded-br-xl ml-n1">
                              <img src="../assets/nyasha.jpg"/>
                            </v-list-item-avatar>
                            </span>
                          </v-card-text>
                          
                        </v-list-item-content>
                      </v-list-item>
                    </v-card>
                </v-col>
                <v-col cols="12" sm="6" >
                  <h3 class="mx-10">My approval <el-button class="morebutton ml-16 my-3" >More<i class="el-icon-arrow-right"></i></el-button></h3>
                    <v-card class="mx-3 rounded-tl-xl rounded-tr-xl rounded-bl-xl rounded-br-xl" color="blue">
                      <v-list-item>
                        <v-list-item-content class="generalfont">
                          <v-card-text align="left"> <span class="white--text">
                            Anytime we can inspire a smile in another, that's a good thing
                            <br>
                            <v-list-item-avatar tile size="12" class="fortime">
                            <img src="../assets/time.png"/>
                            </v-list-item-avatar>
                            <span class="timedisplay ">2020-09-09 10:00am</span>
                            <v-list-item-avatar tile size="16" class="rounded-tl-xl rounded-tr-xl rounded-bl-xl rounded-br-xl ml-2">
                              <img src="../assets/nyasha.jpg"/>
                            </v-list-item-avatar>
                            <v-divider/>
                            Anytime we can inspire a smile in another, that's a good thing
                            <br>
                            <v-list-item-avatar tile size="12" class="fortime">
                            <img src="../assets/time.png"/>
                            </v-list-item-avatar>
                            <span class="timedisplay ">2020-09-09 10:00am</span>
                            <v-list-item-avatar tile size="16" class="rounded-tl-xl rounded-tr-xl rounded-bl-xl rounded-br-xl ml-2">
                              <img src="../assets/nyasha.jpg"/>
                            </v-list-item-avatar>
                            
                            </span>
                          </v-card-text>
                          
                        </v-list-item-content>
                      </v-list-item>
                    </v-card>
                </v-col>
                <v-col cols="12" sm="6" >
                  <h3 class="ml-9">Waiting for approval <el-button class="morebutton ml-5 mb-2" >More<i class="el-icon-arrow-right"></i></el-button></h3>
                    <v-card class="mx-3 rounded-tl-xl rounded-tr-xl rounded-bl-xl rounded-br-xl" color="#add8e6">
                      <v-list-item>
                        <v-list-item-content class="generalfont">
                          <v-list-item-title class="headline mb-1">
                          </v-list-item-title>
                          <v-card-text> <span class="black--text">
                            Anytime we can inspire a smile in another, that's a good thing
                            <i class="fas fa-ellipsis-v"></i>
                            <br>
                            <v-list-item-avatar tile size="12" class="fortime">
                            <img src="../assets/time.png"/>
                            </v-list-item-avatar>
                            <span class="timedisplay ">2020-09-09 10:00am</span>
                            <v-list-item-avatar tile size="16" class="rounded-tl-xl rounded-tr-xl rounded-bl-xl rounded-br-xl ml-2">
                              <img src="../assets/nyasha.jpg"/>
                            </v-list-item-avatar>
                            <v-divider/>
                            Anytime we can inspire a smile in another, that's a good thing
                            <br>
                            <v-list-item-avatar tile size="12" class="fortime">
                            <img src="../assets/time.png"/>
                            </v-list-item-avatar>
                            <span class="timedisplay ">2020-09-09 10:00am</span>
                            <v-list-item-avatar tile size="16" class="rounded-tl-xl rounded-tr-xl rounded-bl-xl rounded-br-xl ml-2">
                              <img src="../assets/nyasha.jpg"/>
                            </v-list-item-avatar>
                                        
                            </span>
                          </v-card-text>
                          
                        </v-list-item-content>
                      </v-list-item>
                    </v-card>
                </v-col>
                <v-col cols="12" sm="12">
                  <h3 class="ml-15">Information <el-button class="morebutton ml-16 mb-2" >More<i class="el-icon-arrow-right"></i></el-button></h3>
                    <v-card class="mx-6 rounded-tl-xl rounded-tr-xl rounded-bl-xl rounded-br-xl" color="#E5E5E5">
                      <v-list-item>
                        <v-list-item-content class="">
                          <v-list-item-title>
                          </v-list-item-title>
                           <v-card-text>
                             <v-col cols="12" sm="12"  class="yellowbox" align=center>人
                            </v-col>
                <span class="black--text">冬令时开始，我们时间改为5：00下班，请大家遵守考勤。</span>
                <v-list-item-avatar tile size="12" class="fortime ml-16">
                <img src="../assets/time.png"/>
                </v-list-item-avatar>
                <span class="timedisplay ">2020-09-09 10:00am</span>
                    
                <i class="fas fa-ellipsis-v ml-16"></i>
                          </v-card-text>
                        </v-list-item-content>
                      </v-list-item>
                    </v-card>
                </v-col>
                <v-col cols="12" sm="12">
                    <v-card class="mx-6 rounded-tl-xl rounded-tr-xl rounded-bl-xl rounded-br-xl" color ="#959595">
                      <v-list-item>
                        <v-list-item-content class="">
                          <v-list-item-title class="headline mb-1">
                          </v-list-item-title>
                           <v-card-text>
                             <v-col cols="12" sm="12" class="bluebox" align=center>宣
                            </v-col>
                <span class="black--text">冬令时开始，我们时间改为5：00下班，请大家遵守考勤。</span>
                <v-list-item-avatar tile size="12" class="fortime ml-16">
                <img src="../assets/time.png"/>
                </v-list-item-avatar>
                <span class="timedisplay ">2020-09-09 10:00am</span>
                
                <i class="fas fa-ellipsis-v ml-16"></i>
                          </v-card-text>
                        </v-list-item-content>
                      </v-list-item>
                    </v-card>
                </v-col>
                <v-col cols="12" sm="12">
                    <v-card class="mx-6 rounded-tl-xl rounded-tr-xl rounded-bl-xl rounded-br-xl" color="#E5E5E5">
                      <v-list-item>
                        <v-list-item-content class="">
                          <v-list-item-title class="headline mb-1">
                          </v-list-item-title>
                           <v-card-text>
                             <v-col cols="12" sm="12" class="redbox" align=center>行
                            </v-col>
                <span class="black--text mr-6">冬令时开始，我们时间改为5：00下班，请大家遵守考勤。</span>
                <v-list-item-avatar tile size="12" class="fortime ml-16">
                <img src="../assets/time.png"/>
                </v-list-item-avatar>
                <span class="timedisplay ">2020-09-09 10:00am</span>
                
                
                <i class="fas fa-ellipsis-v ml-10"></i>
                          </v-card-text>
                        </v-list-item-content>
                      </v-list-item>
                    </v-card>
                </v-col>
        
              </v-row>
          </v-container>
        </v-app>
      </v-flex>
       <v-flex md4>
        <v-app :style="{background: $vuetify.theme.themes.light.background}">
          <v-container>
              <v-row>
                <v-col cols="12" sm="12">
                    <v-card class="mx-6 rounded-tl-xl rounded-tr-xl rounded-bl-xl rounded-br-xl mt-n4 py-4" color="white" >
                      <v-list-item three-line>
                        <v-list-item-content class="pa-2">
                          <v-list-item-title class="headline mb-1">Calendar <br><v-calendar/>
                          </v-list-item-title>
                        </v-list-item-content>
                      </v-list-item>
                    </v-card>
                </v-col>
                <v-col cols="12" sm="12">
                  <h5 class="ml-16">Announcement 
                    <el-button class="morebutton ml-16 " >More<i class="el-icon-arrow-right"></i></el-button></h5>
                </v-col>
                <v-col cols="12" sm="12">
                  <v-card class="mx-6 rounded-tl-xl rounded-tr-xl rounded-bl-xl rounded-br-xl mt-n4 py-4" color="white" >    
                    <v-list-item-content class="pa-2">
                      <v-list-item-title >First heading</v-list-item-title>
                        <v-card-text>Listen to your favorite artists and albums whenever and wherever, online and offline.
                          &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<i class="fas fa-ellipsis-v"></i>
                        </v-card-text>
                        <v-divider/>
                        <v-list-item-title>Second heading</v-list-item-title>
                          <v-card-text primary-title class="justify-center">Lorem ipsum dolor sit amet, consectetur adipisicing elit
                            <i class="fas fa-ellipsis-v"></i>
                          </v-card-text>
                    </v-list-item-content>
                  </v-card>
                </v-col>
                <v-col cols="12" md="12">
                  
                  <v-card class="mx-6 rounded-tl-xl rounded-tr-xl rounded-bl-xl rounded-br-xl mt-n4 " color="white" >
                    
                    <v-card-text align="right">2020/09/09<br>Thursday</v-card-text>
                    
                    <v-card-text align="center" class="degree ml-12">23℃</v-card-text>
                    <v-list-item-avatar tile size="80" >
                        <img src="../assets/sun.png"/>
                      </v-list-item-avatar>
                    <v-divider></v-divider>
                    
                    <v-card-text align="right">
                      Overcast <span class="textH ml-6">|</span><span class="ml-6">jiaxing</span>
                    </v-card-text>
                    <v-divider></v-divider>
                    <v-list align="center">
                  <v-list-item align="">
                    <v-list-item-title class="weatherdetails">P.M2.5</v-list-item-title>
                    <v-list-item-title class="weatherdetails">Speed</v-list-item-title>
                    <v-list-item-title class="weatherdetails">Humidity</v-list-item-title>
                  </v-list-item>
                  
                  <v-list-item class="mt-n5" align="">
                    <v-list-item-subtitle>97</v-list-item-subtitle>
                    <v-list-item-subtitle>9.0kph</v-list-item-subtitle>
                    <v-list-item-subtitle>62.0%</v-list-item-subtitle>
                  </v-list-item>
                </v-list>
                  
                  
                  </v-card> 
                </v-col>
              </v-row>
          </v-container>
        </v-app>
      </v-flex>
    </v-layout>
  </v-app>
</template>
<script>
export default {
  data: () => ({

  }),
  
  computed: {
    theme() {
      return this.$vuetify.theme.dark ? "dark" : "light";
    }
  }
  
};
</script>
<style scoped>
.timedisplay{
  font-size: x-small;
}
.redbox{
  width: 56px;
height: 50px;
background: #E8523F;
border-radius: 10px;
display:inline-block;
font-family: 'Franklin Gothic Medium';
}
.bluebox{
  width: 56px;
height: 50px;
background: #848DF4;
border-radius: 10px;
display:inline-block;
font-family: 'Courier New', Courier, monospace;
}
.yellowbox{
  width: 56px;
height: 50px;
background: #F8B849;
border-radius: 10px;
display:inline-block;
font-family: 'Courier New', Courier, monospace;

}
.morebutton{
width: 108px;
height: 40px;
background: #EFF3FB;
border-radius: 5px;
}
.headingings{
  padding :10px;
} 
.degree{
  font-size: 60px;
}
.weatherreport{
  font-size: 12px;
}
.textH{
  font-size: 54px;
}
.weatherdetails{
  font-size: small;
}
.generalfont{
  font-family:Verdana, Geneva, Tahoma, sans-serif;
}
.innertext{
  font-size: 12px;
}
.innerpadding{
  padding-left: 30px;
}
</style>
