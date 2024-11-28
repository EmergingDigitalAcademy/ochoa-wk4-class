# Ochoa Tier 1 Week 4Week 4 class is remote via Google Meets. | [Video](https://vimeo.com/manage/videos/1034305284/119c6efbca)

### Encourage people to work together

- Any study groups?
- Any planned study groups?

Content Notes

### Terms

- Talk about them as you work through the code snippet

- let in all for loops, for...of
- Differences between loops
- Accessing an item in an array
- index vs value at index (i and array[i])
- Good habits: commenting your code
- Good habits: committing often with commit messages (trick of starting with "this will")

### Code Snippet:

Start with the comment. Pause at different points and have students enter what they think will be logged in the chat and then say "hit enter in 3... 2... 1... enter!"

```js
// 10. Reassign myValue` to 3. Then, loop through your array, logging the value
//     of each array item. If any item matches myValue, then also log "Hurray!"
let myValue = 3;
let numbers = [3, 5, 7, 10];

for (let i = 0; i < numbers.length; i++) {
  console.log('Item value is', numbers[i]);
  if (numbers[i] === myValue) {
    console.log('Hurray!');
  }
}
```

### Discussion

- What do you do when you're getting frustrated?
- Practical Teamwork: Imposter Syndrome

### Q&A
