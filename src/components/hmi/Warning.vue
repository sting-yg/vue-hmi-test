<template>
    <div class="border">
        <div class="border-title">
            <span>Warning</span>

        </div>
        <table>
            <tr>
                <td>이름</td>
                <td>------------</td>               
                <td>서브 코드</td>
                <td>------------</td>
                <td>리스크</td>
            </tr>
            <tr>
                <td>{{ a }}</td>
                <td>------------</td>
                <td>{{ a }}</td>
                <td>------------</td>
                <td>{{ a }}</td>
            </tr>
        </table>

    </div>
    
  </template>
  
  <script>
  export default {
    data(){
        return{
            a: 1
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
}</style>