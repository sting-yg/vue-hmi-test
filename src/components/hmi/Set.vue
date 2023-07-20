<template>
    <div class='set-panel'>
        <div class="border">
            <div class="border-title">
                <span>Set:</span>

            </div>
        </div>

   
        <div class="container">


            <div class="column">
                <h3>Mode</h3>

                <form>

                    <input type="checkbox" id="option1" name="option1" value="option1">
                    <label for="option1">None </label>
                    <br>


                    <input type="checkbox" id="option2" name="option2" value="option2">
                    <label for="option2">Manual </label>
                    <br>


                    <input type="checkbox" id="option3" name="option3" value="option3">
                    <label for="option3">Auto </label>
                    <br>


                    <input type="checkbox" id="option4" name="option4" value="option4">
                    <label for="option3">SemiAuto </label>
                    <br>

                </form>
            </div>

            <div class="column">
                <div class="harf-height">
                    <button class="btn" id="start-btn">START</button>
                    <button class="btn" id="reset-btn">RESET</button>
                </div>
                <div class="harf-height">
                    <button class="btn" id="stop-btn">STOP</button>
                    <button class="btn" id="buzzerstop-btn">BUZZERSTOP</button>
                </div>
            </div>

            <div class="column">
                <h3>SemiAutoCommand</h3>
                <form>

                    <input type="checkbox" id="option1" name="" value="option1">
                    <label for="option1">None </label>

                    <br>


                    <input type="checkbox" id="option2" name="option2" value="option2">
                    <label for="option2">Manual </label>

                    <br>


                    <input type="checkbox" id="option3" name="option3" value="option3">
                    <label for="option3">Auto </label>
                    <br>


                    <input type="checkbox" id="option4" name="option4" value="option4">
                    <label for="option3">SemiAuto </label>
                    <br>

                    <input type="checkbox" id="option3" name="option5" value="option5">
                    <label for="option3">Auto </label>
                    <br>


                    <input type="checkbox" id="option4" name="option6" value="option6">
                    <label for="option3">SemiAuto </label>
                    <br>

                </form>


            </div>
            <div class="column">
                <h3>목표노드</h3>
                <input class="text" type="text" name="RichTextBox_TargetNode" id="">
                <br>
                <button class="btn2">명령생성</button>
            </div>
            <div class="column">

                <button class="btn2">Manual_1 Complete</button>
                <button class="btn2">Manual_2 Complete</button>
                <button class="btn2">Manual_3 Complete</button>
            </div>
        </div>
        <div class="container">
            <div class="column4">

                <div class="row">
                    <button class="">전진</button>
                </div>
                <div class="row">
                    <button class="">좌회전</button>
                    <button class="">우회전</button>
                </div>
                <div class="row">
                    <button class="">후진</button>
                </div>

            </div>
            <div class="column4">
                <div>
                    <button class="btn2">상승</button>
                    <button class="btn2">하강</button>
                </div>
                
            </div>
            <div class="column4">
                <div class="harf-height">
                    <button class="btn">QR 전진 이동</button>
                    <button class="btn">QR 이동 전진</button>
                </div>
                <div class="harf-height">
                    <button class="btn">QR 후진 이동</button>
                    <button class="btn">QR<br>티칭</button>
                </div>
            </div>
            <div class="column4">
                <div class="harf-height">
                    <button class="btn">PIO Bypass</button>
                    <button class="btn">Obstacle Bypass</button>
                </div>
                <div class="harf-heigth">
                    <button class="btn">SetPos Bypass</button>
                </div>
            </div>
        </div>





    </div>

    <div class="container">
  <button class="arrow-button up-arrow">
    <span class="arrow-text">Up</span>
  </button>
  <button class="arrow-button down-arrow">
    <span class="arrow-text">Down</span>
  </button>
  <button class="arrow-button left-arrow">
    <span class="arrow-text">Left</span>
  </button>
  <button class="arrow-button right-arrow">
    <span class="arrow-text">Right</span>
  </button>
</div>
</template>
  
<script>
export default {
    components: {

    }
}

</script>
  
<style scoped>

.container {
    display: flex;
}

.container2 {
    display: flex;
    flex-direction: column;
    align-items: center;
}

.row {
    display: flex;
    justify-content: center;
}

button {
    margin: 5px;
    padding: 10px 20px;
}

.btn {

    width: 45%;
    height: 70px;
    margin-left: 2px;
    margin-top: 2px;
    margin-right: 2px;
    margin-bottom: 2px;
}

.btn2 {

    width: 96%;
    height: 70px;
    margin-left: 2px;
    margin-top: 2px;
    margin-right: 2px;
    margin-bottom: 2px;
}

.harf-width {
    width: 50%;
    /* border: 1px solid black; */
    /* padding: 10px; */
}

.harf-height {
    height: 50%;
    /* border: 1px solid black; */
    /* padding: 10px; */
}

.column {
    flex-basis: 20%;
    /* Distributes the width equally among the columns */
    padding: 10px;
    /* border: 1px solid #000; */
}

.column4 {
    flex-basis: 25%;
    /* Distributes the width equally among the columns */
    padding: 10px;
    /* border: 1px solid #000; */
}


.set-panel {

    width: 1000px;
    height: 860px;
    border: 1px solid black;


}



.text {

    width: 95%;
    height: 50px;
    margin-left: 2%;
    margin-top: 2%;
    margin-right: 2%;
    margin-bottom: 2%;
}
</style>