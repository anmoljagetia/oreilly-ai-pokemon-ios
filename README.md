# O'Reilly AI Pokemon (iOS)
The repo that contains the code for the iOS implementation of the Pokedex app at the O'Reilly AI Conf London, 2018. A lot of this code has been adapted from the sample Tensorflow Image recognition app. The custom model was trained and deployed, with some minor changes in the params and hyperparams.

To run this repo, install Xcode, Cocoapods and the iOS Simulator along with the build tools. The rest of the dependencies are easily pulled down using cocoapods.

An important point to note here, is the size of the trained model, which is close to 5M, and it can do the classification in an average of 30ms, resulting in a very comfortable 30 FPS refresh rate.
