This folder contains 10 images, and for each image there are a number of different judgements (a single judgement is one persons opinion about what the annotation should look like).

For each image you have a corresponding .json file that contains all of the judgements for said image. The top-level key-value pairs of the .json file correspond to judgement_number - judgement. In turn, each judgement corresponds to a list of objects, where each object contains a number of different keys that inform you about the object-class, position of the extreme points (top, right, left, bottom) and so on. 

NOTE! The origin (0, 0) is defined as the top-left corner of the image. As such, the extreme points `Top` and `Bottom` are defined with respect to this coordinate system. 