# IR_Driver_Gaze_Estimation
Based on IR camera, implmented with Caffe

-TRAINING from Scratch-
bin\caffe train --solver=ir_gaze_solver.prototxt --gpu=0

-TRAINING from Weights-
bin\caffe train --solver=ir_gaze_solver.prototxt --weights=caffemodels/***.caffemodel --gpu=0

For the test, the ir_gaze_solver.deploy can be utilized.