# my-git-repo

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Quisque finibus mollis varius. Donec et gravida nibh. Curabitur non quam sodales, euismod velit sed, finibus ante. Ut eu ullamcorper felis. Cras et lorem volutpat, auctor lectus at, finibus risus. Vestibulum cursus pretium massa egestas sollicitudin. Integer elementum dui sem, sit amet fermentum sem sagittis ut. Integer in sem et nibh porta aliquam ut ut sapien. Curabitur vitae mattis felis. Mauris eu pharetra velit. Fusce tempor condimentum erat, eget tincidunt tellus tempus mollis. Nunc vulputate tristique lacus at gravida. Vestibulum ornare pharetra lectus. 

## Sed volutpat

Sed volutpat ligula arcu, sit amet viverra lacus dignissim eget. Integer gravida felis interdum ipsum venenatis, sit amet semper diam malesuada. Pellentesque vitae leo erat. Curabitur in orci sed nunc aliquet consequat. Sed faucibus, neque et maximus pellentesque, orci neque ullamcorper eros, cursus placerat ante erat in nisl. Donec egestas at ante vitae auctor. Integer dapibus nisi vitae massa vestibulum tristique. Nulla eu semper purus. 

#### Сгенерировано 5 абзацей, 450 слов, 2973 байтов Lorem Ipsum

# Fibonacci

```ts
function fib(n: number): number {
   if (n < 1) {
      return 1;
   }
   let a = 1,
      b = 1;
   for (let i = 1; i < n; i++) {
      [a, b] = [b, a + b];
   }
   return b;
}
```