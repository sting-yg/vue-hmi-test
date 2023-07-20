<template>
    <div class="border">
        <div class="border-title">
            <span>Set:</span>
        </div>
        <div class="container">
            <div class="item">
                <!-- 第一列的内容 -->
                <table>
                    <tr>
                        <th>Mode</th>
                    </tr>
                    <tr>
                        <td>
                            <input type="checkbox" value="">
                            <label>None</label>
                        </td>
                    </tr>
                    <tr>
                        <td>
                            <input type="checkbox" value="">
                            <label>Manual</label>
                        </td>
                    </tr>
                    <tr>
                        <td>
                            <input type="checkbox" value="">
                            <label>SemiAuto</label>
                        </td>
                    </tr>
                    <tr>
                        <td>
                            <input type="checkbox" value="">
                            <label>Auto</label>
                        </td>
                    </tr>
                </table>
            </div>
            <div class="item">
                <!-- 第二列的内容 -->
                <table>
                    <tr>
                        <td><button>START</button></td>
                        <td><button>RESET</button></td>
                    </tr>
                    <tr>
                        <td><button>STOP</button></td>
                        <td><button>BUZZERSTOP</button></td>
                    </tr>
                </table>
            </div>
            <div class="item">
                <!-- 第三列的内容 -->
                <table>
                    <tr>
                        <th>SemiAutoCommand</th>
                    </tr>
                    <tr>
                        <td>
                            <input type="checkbox" value="">
                            <label>None</label>
                        </td>
                    </tr>
                    <tr>
                        <td>
                            <input type="checkbox" value="">
                            <label>Manual</label>
                        </td>
                    </tr>
                    <tr>
                        <td>
                            <input type="checkbox" value="">
                            <label>SemiAuto</label>
                        </td>
                    </tr>
                    <tr>
                        <td>
                            <input type="checkbox" value="">
                            <label>Auto</label>
                        </td>
                    </tr>
                </table>
            </div>
            <div class="item">
                <!-- 第四列的内容 -->
                <table>
                    <tr>
                        <th>목표노드</th>
                    </tr>
                    <tr>
                        <td>
                            <input type="text" value="">
                        </td>
                    </tr>
                    <tr>
                        <td>
                            <button>명령생성</button>
                        </td>
                    </tr>
                </table>
            </div>
            <div class="item">
                <!-- 第五列的内容 -->
                <table>
                    <tr>
                        <td>
                            <button>Manual_1Completed</button>
                        </td>
                    </tr>
                    <tr>
                        <td>
                            <button>Manual_2Completed</button>
                        </td>
                    </tr>
                    <tr>
                        <td>
                            <button>Manual_3Completed</button>
                        </td>
                    </tr>
                </table>
            </div>
        </div>
        <div class="container">
            <div class="item">
                <!-- 第一列的内容 -->
                <div class="row">
                    <button class="btn">전진</button>
                </div>
                <div class="row">
                    <button class="btn">좌회전</button>
                    <button class="btn">우회전</button>
                </div>
                <div class="row">
                    <button class="btn">후진</button>
                </div>
            </div>
            <div class="item">
                <!-- 第二列的内容 -->
                <table>
                    <tr>
                        <td><button>상승</button></td>
                    </tr>
                    <tr>
                        <td><button>하강</button></td>
                    </tr>
                </table>
            </div>
            <div class="item">
                <!-- 第三列的内容 -->
                <table>
                    <tr>
                        <td><button>QR 전진 이동</button></td>
                        <td><button>QR 이동 정지</button></td>
                    </tr>
                    <tr>
                        <td><button>QR 후진 이동</button></td>
                        <td><button>QR 티칭</button></td>
                    </tr>
                </table>
            </div>
            <div class="item">
                <!-- 第四列的内容 -->
                <table>
                    <tr>
                        <td><button>PIO Bypass</button></td>
                        <td><button>Obstacle Bypass</button></td>
                    </tr>
                    <tr>
                        <td><button>SetPos Bypass</button></td>                        
                    </tr>
                </table>

            </div>
        </div>
    </div>
</template>
<script>
</script>
<style>
.border {
    width: 100%;
    height: 100%;
    margin-top: 1%;
    margin-left: 1%;
    border: 2px solid black;
    border-radius: 4px;
}
.border-title {
    width: 110px;
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
button {
    width: 120px;
    height: 70px;

    font-size: 12px;
}
.btn {
    width: 100px;
    height: 50px;
    margin-top: 5px;
    margin-bottom: 5px;
    margin-left: 20px;
    margin-right: 20px;

    font-size: 7px;
}
.row {
    display: flex;
    justify-content: center;
}
</style>