# Core Code :rocket: "Readme Dante"

### Interpreted And Compiled Programming Languages 

- Compiled Languages
It is a language that is converted into binary code, when the programmer sends the code to the machine it is transformed into machine code. The language is rebuilt once the programmer is "done" testing the code.

- Interpreted Languages
The interpreted language is converted line by line in real time, without the need for an extra compilation or conversion step.


### Is Java compiled or interpreted, or both? 
- JAVA It is a language that is compiled into a program called BYTECODE, and then passed through a visual machine that interprets it to finally pass it to the CPU. Also called JUST IN TIME, this method is used to improve the performance of the interpreted programs.


### Pseudocode Currency Converter 
START 
DOLLAR <-- GET 
BITCOIN <-- GET  
TOTAL <-- DOLLAR * BITCOIN
 PRINT “Write amount of dollars to convert” 
READ DOLLAR
 PRINT " Enter the price of bitcoin"
READ BITCOIN
PRINT “the total bitcoin would be“, TOTAL
END

### Your date of birth in the matrix? 
- 11011   01   1101001


### Print special numbers:

        //ciclo for
        for(numero = 0; numero <= 200; numero +=2){
        document.write(numero + ",");
        }

        //ciclo while
        let numeros = 0;
        while(numeros <= 101){
            document.write(numeros + ",");
            numeros += 2;
        }

        //ciclo do while
        var num = 0;
        do {
            if(num % 2 ==0)console.log(num);
        }while (num + ",")

### Bad Code
- because the variable was already assigned with the false value and it is not necessary to assign that value again, but rather it is necessary to make a comparison

        var cond = false;
        if (cond == false) {
          document.write('The cond variable is true');
        } else {
          document.write('The cond variable is false');
        }

### Bad code 2

        var n = 100;
        
        if (n == 100) {
          console.log('This is a special number!');
        }
        else if (n < 1000 && n % 10 == 0) {
          console.log('This number is almost special');
  
        } else {
          console.log('Just a regular number');
        }
  
WEEK 2
-------------

### Multiply
        
        function multiply(a, b){
        return a * b
        }
        
### ASCII Total

### ASCII Value 

        function getChar(c){
           return String.fromCharCode(c);
        }
### Binary Addition 
        function addBinary(a,b) {
          return (a + b).toString(2);
        }
        
### Student's Final Grade
     function finalGrade(exam, projects) {
      if (exam > 90 || projects > 10) return 100;
      else if (exam > 75 && projects >= 5) return 90;
      else if (exam > 50 && projects >= 2) return 75;
      else return 0; }

### Holiday VIII - Duty Free
    function dutyFree(normPrice, discount, hol){
      return Math.floor(hol / ((discount * normPrice) / 100));
    }

### Twice as old
    function twiceAsOld(dadYearsOld, sonYearsOld) {
    let sum = Math.abs(dadYearsOld - sonYearsOld * 2)
    return(sum)
    }
### Valid Spacing


### Fake Binary
    function fakeBin(x){
      return x.replace(/[1234]/g, '0').replace(/[56789]/g, '1');
    }
    
### Exclamation marks series #2: Remove all exclamation marks from the end of sentence
    function remove (string) {  
      return string.replace(/!+$/g, "");
    }

### Vowel Remover
        function shortcut (string) {
          return string.replace(/[a,e,i,o,u]+/g, "");
        }

### Rock Paper Scissors!
      const rps = (p1, p2) => {
        let rules = { rock: 'scissors', paper: 'rock', scissors: 'paper' };
        if (p1 === p2) return 'Draw!';
        if (p2 === rules[p1]) {
          return 'Player 1 won!';
        }
  return 'Player 2 won!';
};

### Persistent Bugger


WEEK 3
-------------

### Who Likes It? 
     function likes(names) {
       if (names.length == 0) return 'no one likes this';
       if (names.length == 1) return `${names[0]} likes this`;
       if (names.length == 2) return `${names[0]} and ${names[1]} like this`;
       if (names.length == 3)
         return `${names[0]}, ${names[1]} and ${names[2]} like this`;
       return `${names[0]}, ${names[1]} and ${names.length - 2} others like this`;
     }

### Bit Counting 
    return  n.toString(2).replace(/0/, ``).split(``).length
    
    var countBits = function (n) {
    return n
      .toString(2)
      .split('')
      .reduce((total, val) => total + Number(val), 0);
  };

### Your Order, Please 
     function order(words){
       if(!words) return words;
       return words.split(" ").sort((a,b)=>{
        return a.split("").find(x => {return /\d/.test(x)}) > b.split("").find(x => {return /\d/.test(x)})? 1 : -1
       }).join(" ");
       }

### Simple Pig Latin


### Counting Duplicates
    function duplicateCount(text){

      let count = 0
      let obj ={}

      for (let i of text) {
        i = i.toLowerCase()
        if (!obj[i]) {
          obj[i] = 1
        } else {
          obj[1]++
        }
      }
      for (let i in obj) {
        if(obj[i] > 1) {
          count++
        }
      }
      return count
    }

### Decode The Morse Code


### Valid Parentheses
     function validParentheses(parens){
         let openNum = 0;
       for( let i = 0; i < parens.length; i++){
         if (parens.charAt(i) == "(" ) {
           openNum += 1;
         }else{
           openNum -= 1;
         }
         if ( openNum < 0 ){
           return false
         }
       }
       if (openNum === 0){
         return true
       }else {
       return false
       }
     }

## 1st Core Challenge

- Dante Agonizante, Web developer & UX designer. Estudiante de Ingeniería en Tecnologías Computacionales, con 1 año de experiencia en desarrollo y diseño utilizando JavaScript, CSS, Figma, Adobe XD. Considero que me encuentro en el momento adecuado para adquirir experiencia e incorporarme a una empresa tech. Me considero un joven apasionado y curioso por los contenidos digitales, amo los trabajos que estimulan mi creatividad, aprender nuevas habilidades para plasmar lo que me gusta en tantas maneras como que pueda.



