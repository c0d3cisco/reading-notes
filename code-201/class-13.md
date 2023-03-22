# Local Storage

## Local Storage and How To Use It On Websites

1. Why would a developer use local storage for a web application?<br>
Local storage seems very useful when dealing with websites that have large files as it allows for the browser to skip downloading content in future visits to the site. This can also be useful if you are creating a website that is used often in places with poor signal so the heavy content (even if its not that big) can be loaded and you can still have a semi operational site.  
2. What information should not be stored in local storage?<br>
Since local storage can be used by anyone, do not put any store any sensitive information, particularly that of the user's.
3. Local storage can store what type of data? How would you convert it to that type before storing?<br>
Local storage can store any type of data. The trick for this however is using `JSON.stringify()` and `JSON.parse()`. The stringify method is used to turn the value into a string that is formate specifically for the parse method to turn the string back into JavaScript variables.

## Things I want to know more about
