# swift-sandbox
Swift Sandbox(swift-sandbox || swift sandbox) is a docker container with everything you would need to make a swift application in linux.
This is far from complete. The idea is to have a set of c and swift libraries already configured and ready to go out of the box.
Many libraries have variadic functions (functions which take infinite args) which screws up swift when you import them (e.x. printw() in ncurses).
