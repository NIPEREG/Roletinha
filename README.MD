echo "# Roletinha" >> README.md 

git init 

git add README.md 

git commit -m "first commit" 

git branch -M main 

git remote add origin https://github.com/NIPEREG/Roletinha.git

 git push - sua origem principal
 <!DOCTYPE html>

<html>

<head>

  <title>Tabuleiro de Roleta</title>

  <style>

    .roulette-board {

      display: grid;

      grid-template-columns: repeat(4, 1fr);

      grid-gap: 10px;

    }

    

    .number {

      display: flex;

      justify-content: center;

      align-items: center;

      width: 50px;

      height: 50px;

      background-color: lightgray;

      border-radius: 50%;

      cursor: pointer;

    }

    

    .number.selected {

      background-color: red;

      color: white;

    }

  </style>

</head>

<body>

  <div class="roulette-board">

    <div class="number" data-doz="1" data-col="1">1</div>

    <div class="number" data-doz="1" data-col="2">2</div>

    <div class="number" data-doz="1" data-col="3">3</div>

    <div class="number" data-doz="1" data-col="4">4</div>

    

    <div class="number" data-doz="2" data-col="1">5</div>

    <div class="number" data-doz="2" data-col="2">6</div>

    <div class="number" data-doz="2" data-col="3">7</div>

    <div class="number" data-doz="2" data-col="4">8</div>

    

    <div class="number" data-doz="3" data-col="1">9</div>

    <div class="number" data-doz="3" data-col="2">10</div>

    <div class="number" data-doz="3" data-col="3">11</div>

    <div class="number" data-doz="3" data-col="4">12</div>

    

    <div class="number" data-doz="4" data-col="1">13</div>

    <div class="number" data-doz="4" data-col="2">14</div>

    <div class="number" data-doz="4" data-col="3">15</div>

    <div class="number" data-doz="4" data-col="4">16</div>

    

    <div class="number" data-doz="5" data-col="1">17</div>

    <div class="number" data-doz="5" data-col="2">18</div>

    <div class="number" data-doz="5" data-col="3">19</div>

    <div class="number" data-doz="5" data-col="4">20</div>

    

    <div class="number" data-doz="6" data-col="1">21</div>

    <div class="number" data-doz="6" data-col="2">22</div>

    <div class="number" data-doz="6" data-col="3">23</div>

    <div class="number" data-doz="6" data-col="4">24</div>

    

    <div class="number" data-doz="7" data-col="1">25</div>

    <div class
