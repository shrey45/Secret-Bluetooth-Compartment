# Shrey and Henry's Elves (SHelves)

## Project Pre-Planning

### Pre-Planning Links

Here are some links for our project pre-planning

[Project Pre-Planning Document](https://docs.google.com/document/d/1n7HKKgamwmxf23o07j7cTV_iTXT8w2us0Eivl7ezHLk/edit)

[Onshape Document](https://cvilleschools.onshape.com/documents/396c4bae165363b393b80903/w/f6e132cf290feae134ab5437/e/f283a3afb2df00d231ba4060) - We made a basic design of our project in Onshape so we can get an idea of how it is going to look and where all the components would be in the final product.

### Pseudocode

```c++
void setup() {
    
}

void loop() {
    read nfc
    verify legetimatcy of NFC
    send data back
    if nfc is correct
    {release lock}
    
    if nfc is incorrect 
    {send message back and capture hacker}
}
```
### Purchase Documents

[Finances Spreadsheet](https://docs.google.com/spreadsheets/d/1NeZBrL9gGg3-wpjZcSCkW1YLsva8NJrKapRebr1HqUg/edit#gid=0)

[Things to buy](https://docs.google.com/document/d/1pShio0aneYviQ_E5x2Q9ebDooaYmQixlLznzhgxQQnk/edit)

*Note: Documents are pretty informal right now. Will start to cement as time goes on*

### CAD Designs

Some STL files in the repo:
[CADFiles](https://github.com/shrey45/Shrey-and-Henry-s-Elves-SHelves-/tree/main/CADfiles)

Link to Onshape Document
[It's above, but here's it again](#pre-planning-links)

---

## Weekly Targets

### Week 1 - 2/22/21

#### Goal

Our goal for this week is to figure how the Arduino works**

#### Week 1 Summary

We got our parts and we opened up the Arduino. The arduino that we purchased is the Arduino 33 BLE w/headers. Honestly speaking, we have no idea how to operate this thing. We have used Arduino Uno for the entirity of our "enginnering career". We have to do A LOT of research on how this arduino nano works, and how we can get it to pair with NFC. We can normally look on Google for projects similar to ours, and get ideas and inspiration, but apparently no one has done a project using Arduino Nano + NFC. Someone's got to do it sooo... I guess that's us. We researched a dew sites and used the [Arduino Reference on BLE](https://www.arduino.cc/en/Reference/ArduinoBLE) so we could learn more about it. 

**Goal Status - In progress**

#### Links used

(https://www.okdo.com/project/get-started-with-arduino-nano-33-ble) - Just visiting sites to learn more

[Arduino Reference on BLE](https://www.arduino.cc/en/Reference/ArduinoBLE)

---

### Week 2 - 3/1/21

#### Goal

Our goal is to continue working on our NFC research.

**Goal Status -**

#### Week 2 Summary

We had a major FAIL and breakthrough this week. We realized that the arduino we bought doesn't actually have a NFC reader, it's just a chip. That kind of defeated the purpose of having the arduino nano w/nfc. Our breakthrough was that we were able to use BLE instead of NFC. We slightly modified our project to be a bluetooth based compartment rather than NFC based. What happens is that when the arduino nano connects to our device through NRF connect, the box will unlock. We got that working rather easily, and also decided we wanted to have a step 2 for the unlcoking process. We haven't thought of that step though.

#### Links Used

(https://www.okdo.com/project/get-started-with-arduino-nano-33-ble) - Just visiting sites to learn more

[Arduino Reference on BLE](https://www.arduino.cc/en/Reference/ArduinoBLE)

---

### Week 3 - 3/8/21

#### Goal

Our goal is to figure out what a second step to unlocking the compartment.

**Goal Status -**

#### Week 3 Summary

We thought of stating in the code hat if only a registered device connects through BLE, then the box will open. That way other devices that randomly connect can't get in. I looked around the BLE function library and found a function called scanForAddress(). That was to scan for the bluetooth address that the Nano is connecting to. I played around with that for a bit but for some wierd reason, the adress that was popping up on my serial monitor was completely different from what my device's address was. In the end, it eneded up not working how I wanted it to, but I'll kepp working on it.

#### Links Used

[scanForAddress()](https://www.arduino.cc/en/Reference/ArduinoBLEBLEscanForAddress)

[Arduino Reference on BLE](https://www.arduino.cc/en/Reference/ArduinoBLE)

[Arduino Forums](https://forum.arduino.cc/index.php?topic=662680.0)

---

### Week 4 - 3/15/21

#### Goal

Our goal is to figure out what a second step to unlocking the compartment.

**Goal Status -**

#### Week 4 Summary

Honestly, we didn't get much progress in code this week. Still trying to work out how to add a second layer of security and other things. I also was bombarded with a lot of HW including and essay, so... yeah. Next week will be much more productive for code. We did get some prgress in CAD though! Chek out the [CADFiles](https://github.com/shrey45/Shrey-and-Henry-s-Elves-SHelves-/tree/main/CADfiles)


#### Links Used

[Arduino Forums](https://forum.arduino.cc/index.php?topic=662680.0)

[Onshape link](https://cvilleschools.onshape.com/documents/396c4bae165363b393b80903/w/f6e132cf290feae134ab5437/e/29a0a14830e85418dcbea46b)



---

### Week 5 - 3/22/21

This section will be unlocked next week🔒
#### Goal


**Goal Status -**

#### Week 4 Summary


#### Links Used


