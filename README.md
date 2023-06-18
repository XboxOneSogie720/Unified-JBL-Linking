# Topic: JBL Speaker Synchronization Options

### I've come up with different aspects of JBL speaker synchronization options, focusing on JBL Connect, JBL Connect Plus, JBL PartyBoost, and alternative ideas for creating a unified connection. I tried to brainstorm the use of Bluetooth technology to possible emulate proprietary protocols.

# Considerations
- The protocols in question are JBL Connect, JBL Connect Plus, and JBL PartyBoost

- I already know that JBL Connect, JBL Connect Plus, and JBL PartyBoost all utilize Bluetooth technology for wireless connection and synchronization between compatible JBL speakers.

 - Each protocol has a different limit for the amount of speakers you can connect together, so there would be conflict between each protocol in terms of the amount of total devices you could use from each

# Different Methods of Carrying Out the Plan
- Emulating Protocols in an Android/iOS App
    - If I could get behind the protocol used for Connect, Connect Plus, and Partyboost, I could make an app that searches for a signal outputted by one of the speakers, have the user pick which speaker to get the signal from, then emulate and distrubute the signal to each of the other speakers

- Using a dedecated board
    - The board could have a 3.5mm in or Bluetooth in and split the signal to each chip from a real JBL speaker that will then distribute the signal. This means that the other JBL speakers will be able to see their *distributer chip* as a real speaker, possibly reducing conflicts while ultimately providing a smoother experience. Going back to the consideration about the limit of speakers, perhaps if there was a daughter board which was in charge of emulating tons of bands of JBL Connect, that would mean that the first gen Connect could have more than just two at a time.

# App vs. Board Solution
| Solution | Advantages | Disadvantages |
|----------|------------|---------------|
|   App    | Easier to distribute, requires less hardware, free to make, easily modifiable in the future | Harder to make, less stable |
|  Board   | More stable, uses already developed protol | Harder to distribute, requires experimenting with many real products, more expensive to get speakers, boards, and chips to develop and impliment |
