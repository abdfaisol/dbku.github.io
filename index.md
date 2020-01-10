<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <title></title>
    <style media="screen">
      .flex-ctn{
        display: flex;
        background-color: dodgerblue;
        margin: 10px 0;
        height: 200px;
      }
      .flex-ctn > div{
        background-color: #f1f1f1;
        width: 100px;
        margin: 10px;
        font-size: 30px;
        text-align: center;
        line-height: 75px;
      }
      .flex-align-items-center{align-items: center;}
      .flex-align-items-flex-start{align-items: flex-start;}
      .flex-align-items-flex-end{align-items: flex-end;}
      .flex-align-items-stretch{align-items: stretch;}
      .flex-align-items-baseline{align-items: baseline;;}
    </style>
  </head>
  <body>

    <div class="flex-ctn flex-flow flex-align-items-center">
      <div>1</div>
      <div>2</div>
      <div>3</div>
    </div>
    <div class="flex-ctn flex-flow flex-align-items-flex-start">
      <div>1</div>
      <div>2</div>
      <div>3</div>
    </div>
    <div class="flex-ctn flex-flow flex-align-items-flex-end">
      <div>1</div>
      <div>2</div>
      <div>3</div>
    </div>
    <div class="flex-ctn flex-flow flex-align-items-stretch">
      <div>1</div>
      <div>2</div>
      <div>3</div>
    </div>
    <div class="flex-ctn flex-flow flex-align-items-baseline">
      <div><h1>ا</h1></div>
      <div><h6>ب</h6></div>
      <div><h3>ت</h3></div>
      <div><smal>ث</smal></div>
    </div>


  </body>
</html>
