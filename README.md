![image](https://user-images.githubusercontent.com/55536824/204713189-f10266d8-70b5-4dac-8cde-7d6d38b65723.png)


[See the live demo here](https://rifkyzena.github.io/form-validator/)

# form-validator
A form validation website to test my skills on building a secure form on the front-end side. This form will validate multiple inputs from e-mail to password with complexity requirements with the help of Regex.  

## How it works:
![#c5f015](https://placehold.co/15x15/c5f015/c5f015.png) `This website was a labor of love trying to figure out the right Regex for the HTML`

There are 6 fields on this form you need to fill:

1. Full Name Input:
The constraints I have set on this one is that you need to input at least 3 characters and no more than 100 characters.

2. Phone Number Input:
The constraints I have set on this one is that you can only type numbers. The number string are divided by 3, separated by two dashes.

3. Email Address Input:
The constraints I have set on this one is that you need to input a valid email with '@' symbol and .com at the end your answer.

4. Website URL:
The constraints I have set on this one is that whatever website you are about to type in, please include 'https://' at the beginning.

5. Password and Confirm Password:
This one was a bit tricky to set up the required pattern. Basically you will need to include at least 1 uppercase character, 1 lowercase character, and 1 number on your input.

**The message box below the register button will change accordingly depending if you have successfully entered every query or if you did a specific mistake.**

## Resource and references used:
- https://www.w3schools.com/html/html_forms.asp
- https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input
- https://developer.mozilla.org/en-US/docs/Web/CSS/:valid
- https://developer.mozilla.org/en-US/docs/Learn/Forms/Form_validation
- https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/Constraint_validation
- https://html.com/attributes/input-pattern/
- https://regexr.com/3bfsi
- https://developer.mozilla.org/en-US/docs/Web/API/HTMLFormElement/submit_event
- https://www.w3schools.com/jsref/event_preventdefault.asp
- https://css-tricks.com/form-validation-part-1-constraint-validation-html/
