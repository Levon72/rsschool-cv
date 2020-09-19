## Name
Levchenko Stas
## Contact Info
**tel/Telegram:** +375 29 111 41 40 <br>
## Summary
> BNTU student of the Faculty of Information Technologies and Robotics. From the age of 16 I wanted to become a programmer. In the past, a professional sportsman. Now I work as a system administrator and would like to increase my skills in programming. I am a quick learner, purposeful. 4 years was a raid leader and 2 years a guild master in WOW. The goal is to understand programming and all its intricacies. I have the category of candidate master of sports in swimming.
## Skills
* HTML
* CSS
* JS
* 3DS MAX
* Vray
* Photoshop
## Code examples
### It was required to develop a code that prints to the console the largest number of lines sent, which are permutations of each other. And it was necessary to compress the code into the minimum number of bytes.
```
a=process.argv.slice(2);s=x=>x.split('').sort().join('');l=x=>x.length;b=a.map(x=>a.filter(y=>s(x)==s(y)));if(l(b))b[b.reduce((i,r)=>l(r)>l(b[i])?i+1:i,0)].forEach(x=>console.log(x))
```

