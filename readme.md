

Qus.1. What is the difference between getElementById, getElementsByClassName, and querySelector / querySelectorAll?

Ans: getElementById("id") → ID দিয়ে একটিমাত্র element পায়

    getElementsByClassName("class") → class দিয়ে সব element পায় (live collection)

    querySelector("selector") → CSS selector দিয়ে প্রথম element পায়

    querySelectorAll("selector") → CSS selector দিয়ে সব element পায়




Qus.2. How do you create and insert a new element into the DOM?

    Ans: নতুন element তৈরি ও insert করা
     exmple: let div = document.createElement("div");
            div.textContent = "Hello";
            document.body.appendChild(div);




Qus.3 What is Event Bubbling? And how does it work?

    Ans: ইভেন্ট target element থেকে শুরু করে parent এর দিকে ধাপে ধাপে যায়।




Qus.4 What is Event Delegation in JavaScript? Why is it useful?

    Ans: Parent element এ একটিমাত্র listener দিয়ে অনেক child handle করা।

        dynamic element এর জন্য খুব useful।





Qus.5 What is the difference between preventDefault() and stopPropagation() methods?

    Ans: preventDefault() → browser এর default action বন্ধ করে (link, form)

        stopPropagation() → ইভেন্ট parent এ পৌঁছানো বন্ধ করে

