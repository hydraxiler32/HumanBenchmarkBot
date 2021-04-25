# HumanBenchmarkBot
 automation of tasks on human benchmarks using python, just for fun
 
 Here's what I've got working:
 - chimp test
 - typing test
 - aim trainer
 - reaction timer
 
 Everything else is either a work in progress or I haven't started.
 Why did I make this? I was bored and thought this would be something fun to do.
 It's entirely pointless and meaningless but I thought it'd be a bit of a challenge and it would be fun so here I am.
 
 To use, run the scripts when you're on the respective tests, I suppose I could even automate this at some point as well...
 
 Here's how the working stuff currently works:
 - Chimp test: looks for the boxes with numbers on screen with the screen_search library and stores their locations in an array, pyautogui then clicks the locations in order.
 - Typing test: uses Tesseract to recognize text in the box and then types it with pyautogui.write(), 0.03s delay just because. 
 - Aim trainer: searches for the target on screen (also screen_search) and clicks it, to increase performance the target used here is just a small portion of the real target.
 - Reaction time: waits for a certain pixel to turn green and clicks, if it's blue it'll wait 2 seconds before clicking so the user can see how long the computer took.
