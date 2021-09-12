<h1>Types of Common Problems:</h1>
<h3>DOM-related Errors – Keep in Mind the Order of Execution</h3>
<blockquote>SyntaxError</blockquote>

<li>কোডে কিছু মিসিং বা ভুল আছে, যেমনঃ ব্রাকেট, সেমিকোলন, কোলন, কমা।</li>
<li>Solution: কমেন্ট করে প্রবলেম এরিয়া ছোট করার ট্রাই করবো।</li>
<blockquote>ReferenceError<blockquote>
<li>এমন কোনো লিখছেন, যা এখনো ডিফাইন করা হয় নাই।</li>

<li>Common issue: Spelling Mistake</li>

<li>variableName is not defined</li>

<li>functionName is not defined</li>

<li>Solution: বানান ঠিক আছে কিনা চেক করা।</li>

<blockquote>TypeError</blockquote>
<li>আমরা যেই মেথড/প্রোপার্টি ব্যবহার করার ট্রাই করতেছি, সেটা বর্তমান টাইপ এর অব্জেক্ট এর উপর ব্যবহার করা যায় না।
HTMLelement =

Kuddus is a good boy
HTMLelement.innerText HTMLelement.innerHTML HTMLelement.textContent Array/String.length HTMLelement.value

arrayMethod arr.forEach() arr.map() arr.filter() arr.find()

যেগুলো ভ্যালু আকারে পাওয়া যায়, সেগুলো property; যেগুলো ফাংশন আকারে থাকে, সেগুলো হচ্ছে method;

null, বা undefined এর ক্ষেত্রে কোনো প্রোপার্টি বা মেথড এক্সেস করা যায় না + index ও এক্সেস করা যায় না। তার মানে, set ,get করা যায় না।<li>

<li>Uncaught TypeError: can't access property "innerHTML" of null</li>
<li>Uncaught TypeError: Cannot read property</li>
<li>Uncaught TypeError: Cannot set property</li>
<li>TypeError: ‘undefined’ is not a function Explanation: This is an error that occurs in Chrome when you call an undefined function</li>
<li>TypeError: Cannot read property ‘length’ of undefined</li>
<blockquote>Logical Error ( Harder to debug )</blockquote>

<h3>Things we need to keep in mind while debugging</h3>
<li>Try to visualize the code execution</li>
<li>console.log() variables, function calls that you think might have caused issues</li>
<li>Fetch এর জন্য

 [{},{}] {docs: [{}, {}]}</li>
 <blockquote>HW এগুলো নিজে ক্রিয়েট করে প্র্যাক্টিস করবেন। ফেচ এর লিংক ভুল হলে এরর ডীটেক্ট করা TypeError গুলো ReferenceError</blockquote>
