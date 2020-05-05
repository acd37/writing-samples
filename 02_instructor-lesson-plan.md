### 2. Everyone Do: Solving Algorithms (20 min)

- [Click here for CodeSignal challenge](https://app.codesignal.com/public-test/a2kjXwqf8v7vnGnks/7hyvjF58AaTiQW)

- Ask the class the following questions (☝️) and call on students for the answers (🙋):

  - ☝️ What is the first step to getting a job in web development?

  - 🙋 We need to apply!

  - ☝️ What is the interview process for web development?

  - 🙋 Every interview process is different and largely depends on the company. The interviewing process for web development roles are much more rigorous than we are accustomed. However, as a general rule, we can expect to go through several rounds, including technical and behavioral interviews.

  - ☝️ The first interview is often HR or recruiting agency pre-screen call. What's the purpose of this interview?

  - 🙋 Someone from Human Resources or a recruiting agency will hold a brief 10-15 minute phone call interview to give an overview of the role, ask about experience, and oftentimes salary expectations.

  - ☝️ If the pre-screen call goes well, the next interview is most likely with the hiring manager. What is the purpose of this interview?

  - 🙋 The hiring manager is likely to ask questions about experience with specific technologies that are relevant to the position.

  - ☝️ If the interview with the hiring manager goes well, the next interview is most likely technical. What is a technical interview?

  - 🙋 The technical portion of the interview might be an in-person whiteboarding format, or it might be through an online assessment platform, such as HackerRank, to assess technical proficiency.

  - ☝️ If the technical interview goes well, the next interview is likely behavioral. What is the purpose of the behavioral interview?

  - 🙋 This interview is usually used to gauge cultural and personality fit with the team.

  - ☝️ If the behavioral interview goes well, what is the likely next step?

  - 🙋 The next step is likely an offer detailing the compensation package, including salary, benefits and bonus.

  - ☝️ Did anyone attempt the Code Signal algorithm?

- Use student answers to transition to the next activity.

- Open your IDE and review the solution to the Code Signal algorithm:

  - This algorithm is `addTwoDigits`. We are given a two-digit integer `n`. Return the sum of its digits.

  - For example, if `n = 29`, the output should be `addTwoDigits(n) = 11`.

  - The instructions provide the following details regarding input and output:

  ```md
  **[execution time limit] 4 seconds (js)**

  **[input] integer n**

  A positive two-digit integer.

  Guaranteed constraints:
  `10 ≤ n ≤ 99`.

  **[output] integer**

  The sum of the first and second digits of the input number.
  ```

  - We are also provided the following starter code:

  ```js
  function addTwoDigits(n) {}
  ```

- Ask the class the following questions (☝️) and call on students for the answers (🙋):

  - ☝️ What is the first step to solve this problem?

  - 🙋 In order to add two digits, we need to separate the two digit number into two values.

  - ☝️ How would we do that?

  - 🙋 If we convert the number to a string, we can access the values by index.

  ```js
  var stringNum = n.toString();
  ```

  - ☝️ If we converted our number to a string, how can we add the values as numbers?

  - 🙋 We can use `parseInt()` to convert a string to a number.

  - ☝️Right exactly! So we could use something like `parseInt(stringNum[0])`, which would do what we wanted it to! But why do we need to use `parseInt()`?

  - 🙋 If we don't convert the values of `stringNum` back to numbers, they will simply be concatenated as another string. So we can return the sum of both values like this:

  ```js
  return parseInt(stringNum[0]) + parseInt(stringNum[1]);
  ```

- Answer any questions students have before moving to the next activity.
