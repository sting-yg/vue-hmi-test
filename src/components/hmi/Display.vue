<template>
    <div class="border">
        <div class="border-title">
            <span>Display</span>
        </div>

        <table>
            <tr>
                <td>
                    <!-- <p>사이클 타임: {{ a }}</p>
                    <p>모드: {{ a }}</p>
                    <p>현재명령: {{ a }}</p>
                    <p>현재노드: {{ a }}</p>
                    <p>목표노드: {{ a }}</p>
                    <p>X 좌표: {{ a }}</p>
                    <p>Y 좌표: {{ a }}</p>
                    <p>T (각도): {{ a }}</p>
                    <p>오토상태: {{ a }}</p>
                    <p>오토스텝: {{ a }}</p>
                    <p>충전스텝: {{ a }}</p> -->
                    
                    <p>
                        사이클 타임: <br>
                        모드: <br>
                        현재명령: <br>
                        현재노드: <br>
                        목표노드: <br>
                        X 좌표: <br>
                        Y 좌표: <br>
                        T (각도): <br>
                        오토상태: <br>
                        오토스텝: <br>
                        충전스텝: <br>
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
            </tr>

        </table>

    </div>
</template>
  
<script>
export default {
    data(){
        return{
            a : 1
        }
    },
  
    components: {

    }
}

</script>

  
  
<style>
.border {
    width: 100%;
    height: 100%;
    margin-top: 30px;
    margin-left: 20px;
    border: 2px solid black;
    border-radius: 4px;
}

.border-title {
    width: 200px;
    height: 30px;
    background: white;
    text-align: center;
    margin-top: -12px;
    margin-left: 10px;
}

.container {
    display: grid;
    grid-template-columns: repeat(5, 1fr);
    /* 将容器分成四列 */
    grid-gap: 20px;
    /* 可选：设置列之间的间距 */
}
</style>