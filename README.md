new_div
=======

6.111 Project Color Reduction without coregen divider

Commit 1: To have a new divider in place: we need to do two things:
(1) Replace divider.v by a new divider (that does not depend on CoreGen)
(2) Edit Rgb2hsv.v to call to the new divider.
