<template>
    <div class="border">
        <div class="border-title">
            <span>Error</span>
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
            a:2
        }
    },
    components: {

    }
}

</script>
  
<style></style>