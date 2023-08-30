# Alpine-JS
 Alpine JS Practice
## Calculator
<div class="container" x-data="{ first :  '', second: '', operator: '',result:'0' }">
        <h1 x-data="{ Calculator :  'Calculator' }" x-text="Calculator"></h1>
        <input type="text" x-model="first" placeholder="First Number">
        <input type="text" x-model="operator" placeholder="+, -, *, /">
        <input type="text" x-model="second" placeholder="Second Number">
        <button x-on:click="calculate">Calculate</button>
        <span x-text="result"></span>
    </div>
