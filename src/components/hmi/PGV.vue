<template>
    <div class="border">
        <div class="border-title">
            <span>PGV</span>
        </div>
            <table>
                <tr>
                    <td>
                        <p>
                            LaneDirection: <br>
                            X_POS: <br>
                            Y_POS: <br>
                            T_Angle: <br>
                            RP_DetectedRepairTape: <br>
                            LC_NumberOfLane: <br>
                            TAG_DetectedTag: <br>
                            ERR_DetectedErro: <br>
                            NP_NoAbsoluteXPos: <br>
                            WRN_DetectedWarning: <br>
                            CC1_Bit: <br>
                        </p>
                    </td>
                    <td>
                        <p>
                            {{ a }} <br>
                            {{ a }} <br>
                            {{ a }} <br>
                            {{ a }} <br>
                            {{ a }} <br>
                            {{ a }} <br>
                            {{ a }} <br>
                            {{ a }} <br>
                            {{ a }} <br>
                            {{ a }} <br>
                            {{ a }} <br>
                        </p>
                    </td>

                    <td>
                        <p>
                            RL_SelectedRightLane: <br>
                            LL_SelectedLeftLane: <br>
                            NL_NoDetectedLane: <br>
                            ErrorCode: <br>
                            WarningCode: <br>
                            TagNumber: <br>
                            O_Data: <br>
                            S_Data: <br>
                            CC1_Data: <br>
                        </p>
                    </td>
                    <td>
                        <p>
                            {{ a }} <br>
                            {{ a }} <br>
                            {{ a }} <br>
                            {{ a }} <br>
                            {{ a }} <br>
                            {{ a }} <br>
                            {{ a }} <br>
                            {{ a }} <br>
                            {{ a }} <br>
                        </p>
                    </td>
                </tr>
            </table>
        
    </div>
</template>
  
<script>
export default {
    data(){
        return{
            a:0
        }
    },
    components: {

    }
}

</script>
  
<style></style>