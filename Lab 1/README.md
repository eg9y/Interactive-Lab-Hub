

Staging Interaction

\*\***Kaiwen Zhong, Egan Bisma**\*\*

In the original stage production of Peter Pan, Tinker Bell was represented by a darting light created by a small handheld mirror off-stage, reflecting a little circle of light from a powerful lamp. Tinkerbell communicates her presence through this light to the other characters. See more info [here](https://en.wikipedia.org/wiki/Tinker_Bell). 

There is no actor that plays Tinkerbell--her existence in the play comes from the interactions that the other characters have with her.

For lab this week, we draw on this and other inspirations from theatre to stage interactions with a device where the main mode of display/output for the interactive device you are designing is lighting. You will plot the interaction with a storyboard, and use your computer and a smartphone to experiment with what the interactions will look and feel like. 

_Make sure you read all the instructions and understand the whole of the laboratory activity before starting!_



## Prep

### To start the semester, you will need:
1. Read about Git [here](https://git-scm.com/book/en/v2/Getting-Started-What-is-Git%3F).
2. Set up your own Github "Lab Hub" repository by forking the [Interactive-Lab-Hub repository](https://github.com/FAR-Lab/Interactive-Lab-Hub). To get lab updates, simply [use GitHub's "Sync fork" button when new content is available](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/syncing-a-fork).

3. Set up the README.md for your Hub repository (for instance, so that it has your name and points to your own Lab 1). You can [learn how to organize and format your README.md here](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax). Make sure to include links to your submissions so they are easy to find.


### For this lab, you will need:
1. Paper
2. Markers/ Pens
3. Scissors
4. Smart Phone -- The main required feature is that the phone needs to have a browser and display a webpage.
5. Computer -- We will use your computer to host a webpage which also features controls.
6. Found objects and materials -- You will have to costume your phone so that it looks like some other devices. These materials can include doll clothes, a paper lantern, a bottle, human clothes, a pillow case, etc. Be creative!

### Deliverables for this lab are: 
1. 7 Storyboards
1. 3 Sketches/photos of costumed devices
1. Any reflections you have on the process
1. Video sketch of 3 prototyped interactions
1. Submit the items above in the lab1 folder of your class [Github page], either as links or uploaded files. Each group member should post their own copy of the work to their own Lab Hub, even if some of the work is the same from each person in the group.

### The Report
This README.md page in your own repository should be edited to include the work you have done (the deliverables mentioned above). Following the format below, you can delete everything but the headers and the sections between the **stars**. Write the answers to the questions under the starred sentences. Include any material that explains what you did in this lab hub folder, and link it in your README.md for the lab.

## Lab Overview
For this assignment, you are going to:

A) [Plan](#part-a-plan) 

B) [Act out the interaction](#part-b-act-out-the-interaction) 

C) [Prototype the device](#part-c-prototype-the-device)

D) [Wizard the device](#part-d-wizard-the-device) 

E) [Costume the device](#part-e-costume-the-device)

F) [Record the interaction](#part-f-record)

Labs are due on Mondays. Make sure this page is linked to on your main class hub page.

## Part A. Plan 

To stage an interaction with your interactive device, think about:

_Setting:_ Where is this interaction happening? (e.g., a jungle, the kitchen) When is it happening?

_Players:_ Who is involved in the interaction? Who else is there? If you reflect on the design of current day interactive devices like the Amazon Alexa, it’s clear they didn’t take into account people who had roommates, or the presence of children. Think through all the people who are in the setting.

_Activity:_ What is happening between the actors?

_Goals:_ What are the goals of each player? (e.g., jumping to a tree, opening the fridge). 

The interactive device can be anything *except* a computer, a tablet computer or a smart phone, but the main way it interacts needs to be using light.

\*\***Describe your setting, players, activity and goals here.**\*\*
Kitchen Cooking Helper Light

Setting: Kitchen countertop.

Players: Cook, possibly family members nearby.

Activity: A device (like a jar with your phone inside) glows different colors to indicate cooking stages (e.g., simmering → yellow, done → green).

Goal: Help time tasks without sound (useful in shared spaces).


Storyboards are a tool for visually exploring a users interaction with a device. They are a fast and cheap method to understand user flow, and iterate on a design before attempting to build on it. Take some time to read through this explanation of [storyboarding in UX design](https://www.smashingmagazine.com/2017/10/storyboarding-ux-design/). Sketch seven storyboards of the interactions you are planning. **It does not need to be perfect**, but must get across the behavior of the interactive device and the other characters in the scene. 

\*\***Include pictures of your storyboards here**\*\*
1. Starting the Cook
- **Scene:** Cook places the pot on the stove.
- **Device Action:** Device lights up blue to indicate "cooking timer started".
- **Goal:** Confirm that cooking has begun and the device is active.

2. Boiling Stage
- **Scene:** Water in the pot starts bubbling.
- **Device Action:** Device glows bright yellow to show "boiling/simmering".
- **Goal:** Alert the cook without sound, so they know they can reduce heat or add ingredients.

3. Stir Reminder
- **Scene:** Cook gets distracted checking their phone.
- **Device Action:** Device pulses orange every 30 seconds as a reminder to stir.
- **Goal:** Prevent food from sticking/burning. 

4. Cooking Done
- **Scene:** Dish finishes simmering.
- **Device Action:** Device turns green with a steady glow.
- **Goal:** Notify cook that the food is ready.

5. Overcooking Alert
- **Scene:** Cook forgets to remove the pot.
- **Device Action:** Device flashes red quickly to warn that cooking has gone too long.
- **Goal:** Prevent burning or overcooking.

6. Family Member Interaction
- **Scene:** A family member walks in and taps the device to see how long the food will take.
- **Device Action:** Device shows the progress by white light flashing frequency (e.g., the faster, the less time it will take to finish).
- **Goal:** Let others understand cooking status at a glance.

7. End-of-Day Reset
- **Scene:** Cook finishes dinner, cleans up the kitchen.
- **Device Action:** Device slowly fades from green → blue → off, signaling the timer is reset.
- **Goal:** Give closure to the cooking session and be ready for next use.

<img width="590" height="322" alt="image" src="https://github.com/user-attachments/assets/3578827b-284f-40cc-b77b-b113947907b1" />

Alternative Mason Jar Storyboard:

<img width="581" height="705" alt="image" src="https://github.com/user-attachments/assets/c25814a3-8a3b-4604-8a8c-48027d8e5324" />




Present your ideas to the other people in your breakout room (or in small groups). You can just get feedback from one another or you can work together on the other parts of the lab.

\*\***Summarize feedback you got here.**\*\*
* Feedback 1: It needs to be clear to people other than the cook how much time is left on the cooking timer.
    * Integration: We've addressed this by adding a "Family Member Interaction" scene to the storyboard, which demonstrates how others can easily check the remaining cooking time.
* Feedback 2: There should be a distinct signal that the cooking timer has started.
  * Integration: We've incorporated this by adding an example scene in the first storyboard, showing a blue light that clearly indicates the start of the cooking timer.
* For each of these feedbacks, we also think adding textual elements in addition to the color, e.g. text of minutes left along with the flashing light, will synergize well in showing a clear indicator to users of how long the cooking time is left



## Part B. Act out the Interaction

Try physically acting out the interaction you planned. For now, you can just pretend the device is doing the things you’ve scripted for it. 

\*\***Are there things that seemed better on paper than acted out?**\*\*

On paper, the color changes felt clear and easy to follow, but when acting it out, it was sometimes hard to notice the light change while focusing on cooking tasks (like stirring or chopping). The “stir reminder” pulsing every 30 seconds also felt more disruptive in practice than when I imagined it — it interrupted my rhythm instead of blending smoothly into the flow of cooking.

\*\***Are there new ideas that occur to you or your collaborator that come up from the acting?**\*\*

While acting, I realized that the device could also show progressive changes (like gradually shifting from yellow to green) instead of sudden jumps between colors. This would give a more intuitive sense of how close the food is to being done.


## Part C. Prototype the device

You will be using your smartphone as a stand-in for the device you are prototyping. You will use the browser of your smart phone to act as a “light” and use a remote control interface to remotely change the light on that device. 

Code for the "Tinkerbelle" tool, and instructions for setting up the server and your phone are [here](https://github.com/IRL-CT/tinkerbelle).

We invented this tool for this lab! 

If you run into technical issues with this tool, you can also use a light switch, dimmer, etc. that you can can manually or remotely control.

\*\***Give us feedback on Tinkerbelle.**\*\*
* We can be provided a text input to set hex/RGB values instead of approximating the color through selecting the color picker
* The interface can be publicly hosted, where we can create custom rooms. Each room can have any number of tinkerbelles or Jane Wrens. If a jane wren changes the color, it will broadcast to other users of that same room. It’s quite a lightweight web application, so it should be doable to host for the rest of the class


## Part D. Wizard the device
Take a little time to set up the wizarding set-up that allows for someone to remotely control the device while someone acts with it. Hint: You can use Zoom to record videos, and you can pin someone’s video feed if that is the scene which you want to record. 


\*\***Include your first attempts at recording the set-up video here.**\*\*

* Video link: https://youtu.be/9xYkmUGxKsc

Turning on the device: long tap
Turning off the device: long tap
​​Start / Turn On

Wizard action: Long tap (device glows blue).

Cook reaction: Places pot on stove. “Okay, pasta time!”

Turn Off

Wizard action: Long tap (device fades out).

Cook reaction: “All done for today.”


Now, change the goal within the same setting, and update the interaction with the paper prototype. 

\*\***Show the follow-up work here.**\*\*
Changing status (from boiling stage to stir reminder): short tap.

Boiling Stage

Wizard action: Short tap (device changes to yellow).

Cook reaction: “Water’s boiling — time to add pasta.” (drops pasta).

30 seconds later

Stir Reminder

Wizard action: Short tap (device pulses orange).

Cook reaction: “Oh right, I need to stir.” (stirs).

30 seconds later

Done

Wizard action: Short tap (device turns green).

Cook reaction: “Perfect, pasta’s ready.”



## Part E. Costume the device

Only now should you start worrying about what the device should look like. Develop three costumes so that you can use your phone as this device.

Think about the setting of the device: is the environment a place where the device could overheat? Is water a danger? Does it need to have bright colors in an emergency setting?

\*\***Include sketches of what your devices might look like here.**\*\*

**Mason jar lantern** — phone inside a translucent jar → looks like a kitchen gadget.

<img width="587" height="412" alt="image" src="https://github.com/user-attachments/assets/96b9a93a-86e5-487e-8625-0905e4fd4ef6" />

**Apron pocket light** — phone slipped into a cloth pocket on an apron, glowing outward.

<img width="333" height="246" alt="image" src="https://github.com/user-attachments/assets/699a629d-b169-45e2-ad14-37789650228d" />

**Handle of the pot** — phone on the handle of the pot.

<img width="339" height="251" alt="image" src="https://github.com/user-attachments/assets/bd2ad133-a6c1-4d46-bc7b-a6ce371c2466" />


\*\***What concerns or opportunitities are influencing the way you've designed the device to look?**\*\*


## Part F. Record

\*\***Take a video of your prototyped interaction.**\*\*

Video link: https://youtu.be/8jwvfAAqUTw

First Recording Attempt (Cooking Pasta)

Setting: Kitchen counter, pot on stove, phone-as-device glowing different colors (controlled remotely by collaborator using Tinkerbelle or Zoom).

Script:

Scene opens: Cook places pot on the stove.

Device glows blue (cooking started).

Cook: “Okay, pasta time! Let’s get this water boiling.”

Water begins boiling:

Device glows yellow (boiling).

Cook: “Oh, water’s boiling, time to add the pasta.” (drops in pasta).

Stir reminder:

Device pulses orange every 30s.

Cook: “Ah, thanks for the reminder!” (stirs pasta).

Food ready:

Device turns green (done).

Cook: “Perfect, pasta’s ready. Time to drain and serve.”

End scene: Cook happily takes food off stove, device slowly fades to blue → off.


Follow-Up Work (Making Pizza)
Scene opens (Start):

Cook places the pizza dough with toppings into the oven.

Device glows blue (start).

Cook: “Pizza’s in the oven, let’s wait for it to bake.”

Midway (Cooking in Progress):

Device changes to yellow (baking in progress).

Cook: “Cheese is melting and crust is rising — looks good so far.”

Done (Ready to Eat):

Device turns green (perfectly baked).

Cook: “Pizza’s done — time to take it out before it burns!” (removes pizza, smiles).

Overdone (Too Late):

If cook doesn’t remove it in time, device flashes red (overbaked).

Cook: “Oh no! It’s burned — should’ve grabbed it when the green light came on.”

\*\***Please indicate who you collaborated with on this Lab.**\*\*

Egan Gumiwang Pratama Bisma: mason jar storyboard, costume creation, tinkerbelle feedback, video actor
Kaiwen Zhong: Storyboard process design, recording script design, recording narrator
ChatGPT: Storyboard image generation, use-case idea generation

Be generous in acknowledging their contributions! And also recognizing any other influences 
(e.g. from YouTube, Github, Twitter) that informed your design. 



# Staging Interaction, Part 2 

This describes the second week's work for this lab activity.


## Prep (to be done before Lab on Wednesday)

You will be assigned three partners from other groups. Go to their github pages, view their videos, and provide them with reactions, suggestions & feedback: explain to them what you saw happening in their video. Guess the scene and the goals of the character. Ask them about anything that wasn’t clear. 

\*\***Summarize feedback from your partners here.**\*\*

## Make it your own

Do last week’s assignment again, but this time: 
1) It doesn’t have to (just) use light, 
2) You can use any modality (e.g., vibration, sound) to prototype the behaviors! Again, be creative! Feel free to fork and modify the tinkerbell code! 
3) We will be grading with an emphasis on creativity. 

\*\***Document everything here. (Particularly, we would like to see the storyboard and video, although photos of the prototype are also great.)**\*\*


