<!DOCTYPE html>
<html>

<!-- This is head section -->
<head>
    <tittle>
        Aviksha Vidya Koundinya 
    </tittle>
</head>

<!-- This is a body section -->

<body>
    <h1> This is the heading tag! </h1>
    <p> this is a paragraph tag.</p>

    <h3> This is heading 3!</h3>
    <h2> This is heading two </h2>

    <img src="download.png" img/>


    <h1> This is my survey form! </h1>



    <form>

        <label for="name">Name: </label>
        <input type="text" name="name">
        <br>

        <label for="name">email: </label>
        <input type="text" name="name">
        <br>

        <div>

        <label for="name">Age: </label>
        <input type="text" name="name">

        <br>
        <label for="name">Phone number: </label>
        <input type="number" name="name">

        </div>

        <div>
            <fieldset><label>Please select an option:</label>
                <select>
                    <option selected disabled>select an option</option>
                    <option value="">Option 01</option>
                    <option value="">Option 02</option>
                    <option value="">Option 03</option>
                    <option value="">last option</option>
                </select>                
            </fieldset>
        </div>

        <div>
            <fieldset>
                <h2>please check all the boxes relevant:</h2>
            <label><input type="checkbox" name="game">first option</label>
            <br/>
            <label><input type="checkbox" name="movie">second option</label>
            <br/>
            <label><input type="checkbox" name="music">third option</label>
            </fieldset>

        </div>
        
        <div>
            <fieldset>
                <h2>please check all the boxes relevant:</h2>
            <label><input type="radio" name="game">first option</label>
            <br/>
            <label><input type="radio" name="movie">second option</label>
            <br/>
            <label><input type="radio" name="music">third option</label>
            </fieldset>

        </div>

        <div>
            <fieldset>

                <textarea style="height: 100px;width: 200px;">Please provide your comments</textarea>
            </fieldset>
        </div>

        <div>
            pick a date
        </div>

    </form>
</body>
<style>

    table{
       border-collapse: collapse;

    }

    tr,
    th,
    td {
       padding: 20px;
       border: 4px solid black;
       font-size: 40px;
    }
  </style>
</head>
<body>
 <table>
     <caption style >This is my table</caption>
     <tr>
         <th> Name </th>
         <th> Surname </th>
         <th> Age </th>
     </tr>
     <tr>
         <td> Aviksha Vidya </td>
         <td> Koundinya</td>
         <td> 19 </td>
     </tr>
     <tr>
        <td> Gurmannat </td>
        <td> Sandhu</td>
        <td> 19 </td>
    </tr>

     
 </table>
</body>
<style>
    .myDiv{
    border: 5px outset red;
    background-color: lightblue;
    text-align: center;
    }
</style>
</head>
<body>

<!-- Vue App -->
<div id = 'app' class="mydiv">
    <h1>Hello World</h1>
    <h1>{{title}}</h1>
    <h2>{{title}}</h2>
    <h3>{{list}}</h3>
</div>
<div id="app">
    <button @click="count++">
        count is: {{count}}
    </button>
</div>
<!--Script section where you write your vue js code-->
<script type="module">
import {createapp} from 'vue'

createapp({
    data() {
        return {
            title:'Hellow worl vue',
        }
    }
})
</script>
</body>


</html>
