# Balls

![Alt text](example.gif?raw=true "Balls")

### Your task:

Create a centered box, with a drop button. It must be similar to the example gif.
Pressing the drop button yields the following results:

- If there are no balls in the box it inserts a gray ball.

- Every third ball is a green ball.
- Every fifth ball is a blue ball.
- Every fifteenth ball is a purple ball.
- Every other ball is a gray ball

The sum shows the number of balls.

The score shows the sum of the balls scores:
- White Ball:  1
- Green Ball:  3
- Blue Ball:   5
- Purple Ball: 15

Constraints:
- After the view is loaded with the empty box JS takes over, the rendering of the balls must be in JS
- The decision what kind of ball comes next must come from the backend, (drop button fires a request)
- You can't use JS Libraries, no jQuery/Angular/React or any library, just vanilla JS
