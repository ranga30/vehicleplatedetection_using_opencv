#vehicleplatedetection
explanation of code

2 classes:

PossiblePlate

PossibleChar



find plates

find chars within plates


detectPlatesInScene()

detectCharsInPlates()


imgOriginalScene

preprocess()

imgGrayscaleScene, imgThreshScene

findPossibleCharsInScene()

listOfPossibleCharsInScene

findListOfListsOfMatchingChars()

listOfListsOfMatchingCharsInScene

extractPlate()

listOfPossiblePlates




loadKNNDataAndTrainKNN()


listOfPossiblePlates

preprocess()

possiblePlate.imgGrayscale, possiblePlate.imgThresh

findPossibleCharsInPlate()

listOfPossibleCharsInPlate

findListOfListsOfMatchingChars()

listOfListsOfMatchingCharsInPlate

removeInnerOverlappingChars()

listOfListsOfMatchingCharsInPlate

within each possible plate, suppose the longest list of potential matching chars is the actual list of chars

longestListOfMatchingCharsInPlate

recognizeCharsInPlate()

possiblePlate.strChars



listOfPossiblePlates
suppose the plate with the most recognized chars is the actual plate
licPlate










