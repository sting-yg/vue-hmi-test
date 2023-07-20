<template>
  <h3></h3>

  <!-- <Setcopy/>
  <Display/>
  <Warning/>
  <Error/>
  <PGV/>
  <ObstacleDetectSensor/>
  <UpperUnit/>
  <IO/>
  <MotorDrive/>
  <Battery/> -->
  
  <Set/>
  <div>
    <table>
      <tr>
        <td style="width: 80%;"><Setcopy/></td>
        <td style="width: 20%;"><Display/></td>
      </tr>
    </table>
    <table>
      <tr>
        <td style="width: 33%;"><Warning/></td>
        <td style="width: 33%;"><Error/></td>
        <td style="width: 33%;"><PGV/></td>
      </tr>
    </table>
      <table>
      <tr>
        <td style="width: 33%;"><ObstacleDetectSensor/></td>
        <td style="width: 33%;"><UpperUnit/></td>
        <td style="width: 33%;"><IO/></td>
      </tr>
    </table>
    <table>
      <tr>
        <td style="width: 50%;"><MotorDrive/></td>
        <td style="width: 50%;"><Battery/></td>
      </tr>
    </table>  
  </div>

</template>

<script>
import Setcopy from './components/hmi/Setcopy.vue';

import Display from './components/hmi/Display.vue';
import Warning from './components/hmi/Warning.vue';
import Error from './components/hmi/Error.vue';
import PGV from './components/hmi/PGV.vue';
import ObstacleDetectSensor from './components/hmi/ObstacleDetectSensor.vue';
import UpperUnit from './components/hmi/UpperUnit.vue';
import IO from './components/hmi/IO.vue';
import MotorDrive from './components/hmi/MotorDrive.vue';
import Battery from './components/hmi/Battery.vue';

// import Set from './components/hmi/Set.vue';

export default {
  components: {
    
    Setcopy,
    Display,
    Warning,
    Error,
    PGV,
    ObstacleDetectSensor,
    UpperUnit,
    IO,
    MotorDrive,
    Battery,
   
    // Set,
  
  }
}

</script>
<style></style>