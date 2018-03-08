# 100 Days Of Code - Log

### Day 0: March 5, 2018

**Today's Progress**: Learned about Git and Git Bash, and made my first Git Commit!

**Thoughts:** I've been meaning to learn more about Github and Git, but I'd never taken the time to figure out how they work or why they're important as a developer. This is the first step in my quest to share my coding journey. First Github - next, the world!

**Link to work:** [First Github Repo](https://github.com/emilyrhanka/myappsample)

### Day 1: March 7, 2018

**Today's Progress**: Learned more about the .hasOwnProperty function on freeCodeCamp.

**Thoughts:** Still not entirely sure how the problem works. Getting a little hung up on how it understands what values to look for. The solution involves an if/else statement that looks like this:
  var myObj = {
  gift: "pony",
  pet: "kitten",
  bed: "sleigh"
};

function checkObj(checkProp) {
  // Your Code Here
  if (myObj.hasOwnProperty(checkProp)) {
    return myObj[checkProp];
  } else {
    return "Not Found";}
}

// Test your code by modifying these values
checkObj("gift");

I'm having a hard time understanding why it understands what checkProp is if it wasn't previously defined. I'm hoping that I'll understand better as I fill in my knowledge with other resources. I've checked to see if checkProp is just standard syntax, but I can't seem to find anything.
