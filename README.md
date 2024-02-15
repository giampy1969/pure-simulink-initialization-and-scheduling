# pure-simulink-initialization-and-scheduling
Examples showing how to schedule the sequential execution of different subsystems

[![View pure-simulink-initialization-and-scheduling on File Exchange](https://www.mathworks.com/matlabcentral/images/matlab-file-exchange.svg)](https://www.mathworks.com/matlabcentral/fileexchange/54806-pure-simulink-initialization-and-scheduling)

[![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=giampy1969/pure-simulink-initialization-and-scheduling)

SIMULINK&reg; INITIALIZATION AND SEQUENTIAL BLOCK EXECUTION EXAMPLES:
----------------------------------------------------------------

A question often asked by advanced simulink users is how to execute
some part of the model only once at the beginning of the simulation,
and execute another part of the model only after the former is executed.

This is often motivated, for example, by the need to execute some 
diver blocks that perform some initialization function on the hardware, 
before executing other blocks that perform the main intended task.

A related question is how to make sure that some blocks are executed only
sequentially, that is one after the other.

This file contains simple examples showing how to easily perform both 
tasks in a pure-simulink setting.

Note that some hints and examples on how to approach these problems are also
given in the documentation (see below).


CONTENTS:
---------

readme.md               This file.

sim_init_example.slx    Initialization example
sim_seq_example.slx     Sequential Exacution example
sim_initseq_example.slx Combined Initialization and Sequential Execution example

license.txt             License file.
security.md             Security statement.


OTHER APPROACHES DESCRIBED IN THE DOCUMENTATION:
------------------------------------------------

This is a general starting point:

http://www.mathworks.com/help/stateflow/ug/scheduling-execution-of-simulink-subsystems.html

this is an alternating executing subsystem example:

http://www.mathworks.com/help/simulink/ug/triggered-and-enabled-subsystems.html#f4-84472

while this is a stateflow-based solution:

http://www.mathworks.com/help/stateflow/ug/schedule-multiple-subsystems-in-a-single-step.html

and this is a more general explanation of how to display and control the 
execution order, still based on stateflow:

http://www.mathworks.com/help/simulink/ug/controlling-and-displaying-the-sorted-order.html

