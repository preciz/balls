# Balls

The goal of this fullstack excersize is to get to know how you learn, digest and implement new things. We expect you to write production quality code with today’s CSS and Javascript standards and clean object-oriented ruby code.

![Alt text](example.gif?raw=true "Balls")

## Your task

Create a centered box, with a drop button. It must be similar to the example gif.
Pressing the drop button yields the following results:

- If there are no balls in the box it inserts a pink ball.
- Every third ball is a green ball.
- Every fifth ball is a blue ball.
- Every fifteenth ball is a purple ball.
- Every other ball is a pink ball.

The sum shows the number of balls.

The score shows the sum of the balls scores:
- Pink Ball:   1
- Green Ball:  3
- Blue Ball:   5
- Purple Ball: 15

## Constraints

- After the HTML view is loaded with the empty box, JS takes over. No more server rendered HTML tags, no render to string.
- The rendering of the balls must be in JS. no `innerHTML`. You need to dynamically create the balls in JS code.
- The drop button fires a JSON request, sends down the number of balls, the backend responds in JSON which ball colour comes next.
- You can't use JS Libraries, no jQuery/Angular/React or any library, just vanilla JS.

## Bonus

- Use es6, and new browser features
