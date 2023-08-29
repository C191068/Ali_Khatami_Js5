# Ali_Khatami_Js5(Learning from the video of Dave Gray)

### Math methods 

Javascript math objects have both properties and methods <br>

![j39](https://github.com/C191068/Ali_Khatami_Js5/assets/89090776/dd76dc63-702b-4bc0-bfe5-ba1e571e8d8b)
Code:

```
console.log(Math.PI);

```

here the above returns the value of PI <br>


there are more math properties vailable at https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math <br>

Math.trunc returns the integer portion of the number and truncates any decimel <br>


![j40](https://github.com/C191068/Ali_Khatami_Js5/assets/89090776/23715e97-b6fb-4d56-b5b9-07f7a29e086e)

Code:

```

console.log(Math.trunc(Math.PI));

```

we can see the above has converted float type PI to integer type <br>

![j41](https://github.com/C191068/Ali_Khatami_Js5/assets/89090776/ad609d26-cf1f-448e-a931-adcd0f8c7031)
Code: 

```
console.log(Math.round(3.4));

```
the round method returns the value of the number rounded to the nearest integer <br>



![j42](https://github.com/C191068/Ali_Khatami_Js5/assets/89090776/e7e40fce-8157-4f8a-ab2b-3e33da4ca3ce)

When applied to 3.5 it returns 4

![j43](https://github.com/C191068/Ali_Khatami_Js5/assets/89090776/cfc25691-a491-46fe-a91a-fc94e0348a17)

code:

```

console.log(Math.ceil(3.3));

```

if we use the ceil method it will return the round up number <br>
no matter what is after the decimel place <br>


![j45](https://github.com/C191068/Ali_Khatami_Js5/assets/89090776/11a6ab4a-8c48-4362-a804-1fee20bdb9ac)


Code:

```
console.log(Math.floor(3.3));

```

if we use the floor method it will round down the number no matter what is after the decimel place <br>


![j46](https://github.com/C191068/Ali_Khatami_Js5/assets/89090776/09f91a27-beea-4deb-b786-34dee9fe9aed)
Code:

```

console.log(Math.pow(2, 10));

```

the above method takes two arguments base number and the exponent and return the <br>
power of a number <br>


![j47](https://github.com/C191068/Ali_Khatami_Js5/assets/89090776/f5901b48-4ecb-419c-afff-e2a5d32f3b99)

Code:

```
console.log(Math.min(2, 10, 1));

```

the above returns the lowest of all numbers <br>



![j48](https://github.com/C191068/Ali_Khatami_Js5/assets/89090776/9fbcc648-c19c-4ff5-86d5-9b2bf3191ee1)
Code:

```
console.log(Math.max(2, 10, 1));

```
the above retuns the highest number <br>


The math.random is both interesting and useful <br>

![j49](https://github.com/C191068/Ali_Khatami_Js5/assets/89090776/0cc2b7f4-860e-4824-97a1-e7e78f490be9)


It provides pseudo random number from zero to one <br>


![j50](https://github.com/C191068/Ali_Khatami_Js5/assets/89090776/edf20def-c287-46b8-9c04-8041e5d3b75b)

the above returns the random number from 1 to 10 <br>


We shall use the floor method instead of ceil method <br>
to generate random number <br>

If we use seal we won't have to add 1 in our equation <br>

The reason is that math random method generates a number from 0 to 1 <br>

which gives it a very slim chance to simply return zero <br>

therefore using ceil method when genrating a random number also <br>
has a very slim chance to return 0 <br>

so we will use floor method as illustrated to generate number <br>
from 1 to 10 <br>


### Code challenge 

![j52](https://github.com/C191068/Ali_Khatami_JS3/assets/89090776/9c1c00f5-aa51-435e-9797-91c805543d52)

code challenge :Write a code that will return random letter from your nam <br>



### If Statements 

```If statements``` are great introduction to condituionals in programming <br>


they let us to make decision based on current state of data <br>

![j53](https://github.com/C191068/Ali_Khatami_Js5/assets/89090776/f41d417d-5d21-4fe2-b1a6-4702703da6f6)

example of if statement <br>

![j54](https://github.com/C191068/Ali_Khatami_Js5/assets/89090776/d220d973-da29-4d85-97ce-f6bd9df41c39)

example of else statement <br>

the above output the message as undefined which is not goiod at all <br>

![j60](https://github.com/C191068/Ali_Khatami_Js5/assets/89090776/c456625b-4e57-436a-8c90-a4b078044bdc)

thus above is the correct one <br>

let us change the  reply to a message for our cutomer instead <br>


![j55](https://github.com/C191068/Ali_Khatami_Js5/assets/89090776/598f9cd9-ac12-4ba9-a5f3-3f176d2b9af2)

we craete a new variable that will hold boolean data <br>

![j61](https://github.com/C191068/Ali_Khatami_Js5/assets/89090776/b0f45219-f861-4ff1-a213-27c870e601ee)


if the customer bnned is true we will reply no soup for you <br>

because why will we check for a car if tthe customer is banned <br>

they can't buy the car if the car is ready <br>

![j57](https://github.com/C191068/Ali_Khatami_Js5/assets/89090776/48372c69-9197-4384-af2a-4a8996646d83)


we have a new variable that also hold boolean data <br>
and other if else statement <br>


![j58](https://github.com/C191068/Ali_Khatami_Js5/assets/89090776/5199d559-3b77-41f5-9f05-78cddb736966)

we will copy this part and paste it again <br>


![j59](https://github.com/C191068/Ali_Khatami_Js5/assets/89090776/4c820fa0-5e8e-4bbe-9f44-9123f7d830cd)


we have given a new condition for bike <br>

this condition must come before the condition of car <br>

if condition of car was above our condition of car and bike <br>

all orders for car and bike will just stop when condition only for car is true <br>

No one would get the bike <br>

If we don't have logical order correct we can have angy car customers <br>

![j62](https://github.com/C191068/Ali_Khatami_Js5/assets/89090776/d5de08df-9f21-43e4-9261-9ae3001184e9)

here if the customer is banned then the above output is shown <br>

![j63](https://github.com/C191068/Ali_Khatami_Js5/assets/89090776/debf2d5e-2f0b-4de3-9cf8-f7c3f230c9ce)

if the customer is not banned then the above output shows <br>


![j64](https://github.com/C191068/Ali_Khatami_Js5/assets/89090776/20037c07-5513-4de3-8b2c-58ee2481a0a9)

If there is no car then the above shows <br>

![j65](https://github.com/C191068/Ali_Khatami_Js5/assets/89090776/cc3b0b09-7310-45b0-83e4-9c8f0b4f90d0)

No car and no bike then the above output shows <br>

```js


let customerIsBanned = false;
let car;
let bike = false;
let reply;
if (customerIsBanned) {
  reply = `No car & bike for you`;
} else if (car && bike) {
  reply = `here is your ${car} & bike`;
} else if (car) {
  reply = `Here is your ${car}`;
} else if (bike) {
  reply = `Here is your bike`;
} else {
  reply = `Sorry we are out of car & bike`;
}

console.log(reply);

```


![j66](https://github.com/C191068/Ali_Khatami_Js5/assets/89090776/f2126d4f-347f-47a1-80b6-5b97f461820d)

as there is no A+ then the above output is undefined <br>

the logical order of if statement is like waterfall <br>











