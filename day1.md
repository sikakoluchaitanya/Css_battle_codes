## css battle day 1

To recreate the picture shown below using only css.


![user_ummd3POvEDfFyeFvVdOMG3OOrwE2_targets_target_Gt1zODM](./user_ummd3POvEDfFyeFvVdOMG3OOrwE2_targets_target_Gt1zODM.png)

the code: 
``` html 
<p></p><a></a><b></b>
<style>
  *{
    background: #73385A;
  }
  p{
    background: #FCDFEB;
    width: 200px;
    height:200px;
    position:fixed;
    top:34px;
    left:100px;
  }
  a{
    background: #73385A;
    width: 40px;
    height: 80px;
    position:fixed;
    top:170px;
    left:140px;
    box-shadow: -40px 40px #73385A, 80px 0px #73385A, 120px -120px #73385A;}
  b{
    background: #73385A;
    width: 80px;
    height: 40px;
    top:90px;
    left:220px;
    position:fixed;
    box-shadow: 0px 80px #73385A;
  }
</style>
```