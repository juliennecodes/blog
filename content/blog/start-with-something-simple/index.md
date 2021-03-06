---
title: Start With Something Simple
date: "2021-07-03"
---
Starting with something simple was the big lesson I learned in [Pomodoro](https://juliennecodes.github.io/pomodoro/). I learned this the hard way when I made the mistake of writing complex code in the beginning.

The mistake was an understandable one. At this point in time, I found success in writing apps by starting with writing usage notes. Usage notes documented how I wanted the finished apps to be used. I wrote notes on what the user does and what the direct result of that action would be. It was part of my planning process that clarified what features I want built. However, when it came time to write the code, I froze. I didn’t know how to start.

What I didn’t take into account was that my past projects were too simple, which hid the flaws of this approach. The flaws became apparent when the same approach didn’t work for a more complex project like Pomodoro.

Part of the complication was that there were multiple moving mechanisms involved in a pomodoro timer. Starting the timer didn’t just mean the timer counting down, it means keeping track of the timer being active or not, the time remaining, the current session, and the number of pomodoros completed. This was a lot especially when I was just starting.

I told my mentors how I found it difficult to even start the project. The code I wrote was very messy and I was dissatisfied with it. Hearing my problems, it was suggested that I should start with something simple. Once I got a simple feature going, write tests to make sure it keeps working. When that feature is foolproof, work on adding a newer feature backed by tests. Repeat this gradual addition of features and tests until the app is finished.

Writing out the code in steps helped immensely. I started writing the code for just the timer counting down when the start button is clicked. After that feature was working, I wrote code to make sure it wasn’t counting down past zero. After that I introduced work session switching to break session. I slowly built the app by gradually adding features and eventually what started as simple code turned into a complex app.

Learning this lesson was great. It allowed me to hone the process of how I write apps for the better. Making this mistake once was worth it because I was able to make sure I didn’t make it again. I carried this lesson over to other projects and I credit it for smoother experience in writing apps.
