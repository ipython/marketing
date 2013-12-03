Use case: Giving a talk

IPython provides an excellent pedagogical platform.

X is teaching an undergraduate course which has a computational component.

He prepares presentation "slides" as IPython Notebooks, interleaving narrative
text, images, LaTeX formulae, and code.

During a lecture, X wants to demonstrate how students can experiment with tools
he has written with the help of his graduate students.

He prepares code to load up some data and perform some basic analysis.
X can execute the code cells, getting the results in-line in the same
environment that he's writing the rest of the lecture materials.

He can split up the code into several cells: a cell to load the data, which
he'll only need to execute once. Another code cell which perform some analysis,
which is followed by a narrative cells that describes the method used, provides
a rendered formula for the code implementation, suggests how some parameters
might by altered, and provides clickable links to the paper which first
introduced the technique. This is followed by yet another cell to plot a subset
of the data, so he can tweak the plotting parameters, such as line width and
line color and re-execute again until getting a desirable result.

Most importantly, with the boilerplate code out of the way, X does not need to
anticipate *all* of the concept the students may find confusing.

X now has the tools to answer student questions like:

    "What happens if you change parameter B to 23"

    "How much longer would it take if we doubled the dimensions?"

    "Can you re-plot it on a log-log scale?"

The demo gods will smile kindly upon X's work.

At the end of the lecture, he makes the notebook available, so that students
can interact with the in-class demos themselves on their own machines.


Not just for teaching: while giving a technical talk, X retains the ability to
answer specific questions.  The IPython Notebook allows anyone to turn the
analysis portion of computationally driven talks into a social activity.
