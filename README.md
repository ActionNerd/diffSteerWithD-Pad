# diffSteerWithD-Pad
A high level / basic guide for differential steering with a D-Pad (joystick)

Why does this Document Exist?
In the initial stages of a previous project, I was intent on using differential steering to control a robot.  I knew generally how differential steering worked, but I found there wasn't much out there in terms of implementation guides.  Further, I found there was practically NO information available on using a joystick (D-Pad) within the context of differential steering.  This isn't necessarily a difficult topic.  In fact, it's pretty basic, however, it does require a little bit of thought -- it's my intent here to share some of that thought with you.

Now, since I had put this together, someone has posted an extremely useful and detailed article on this exact topic which can be found at https://www.impulseadventure.com/elec/robot-differential-steering.html.  I think there's room for my explainer as well as I intend to have more graphics, less code, and generally be higher level.

What is Differential Steering?
Per Wikipedia: Differential steering is the means of steering a land vehicle by applying more or less drive torque to one side of the vehicle than the other.[1] Differential steering is the primary means of steering tracked vehicles, such as tanks and bulldozers, is also used in certain wheeled vehicles commonly known as skid-steer, and even implemented in some automobiles, where it is called torque vectoring, to augment steering by changing wheel direction relative to the vehicle. Differential steering is distinct from torque steer, which is usually considered a negative side effect of drive-train design choices.

Think of tank treads where a driver controls forward / backward motion of each tread to move the vehicle.
