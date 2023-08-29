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



































