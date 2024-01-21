# disease-netlogo

This cellular-automata simulates diseases spreading and vaccinations. These kinds of cellular automata are not uncommon in research to predict diseases though I was inspired by this simulation by Nicky Case (https://ncase.me/sim/?s=sick) that I saw years ago when I was a teen. Coding it in Netlogo took a bit but it does everything basically as I planned it to do:

The rules are simple:
1. The randomly generated board will contain a percentage of vaccinated people and unvaccinated people. 1 percent of the remaining people will be sick.
2. If a vaccinated or unvaccinated person is adjacent to a sick person, they have a percentage chance of also getting sick.
3. If a vaccinated person triggers this chance of getting sick, they have a certain chance to be protected by their vaccination.
4. If a person is sick, they have a predetermined percentage chance to die.
5. If they did not die, they have a predetermined percentage chance of recovering from the sickness.
6. If a person has recovered from sickness, they cannot gain the sickness anymore.

There are five different parameters that are modifiable: the initial percentage of vaccinated people, the chance of recieving a sickness from a neighbor, the chance of dying from sickness, the chance of recovery from sickness and the effectiveness of the vaccine.

Interesting observations were popping up as a result of mixing and matching the rates. Such examples include:
1. A low sickness rate or a high enough death rate (with vaccinations) can make a disease die out before spreading to everyone.
2. The higher the vaccination rate, the lesser the disease can spread as it can create pockets of protection for those unvaccinated.
3. Despite a high vaccination rate, a slightly lower effectiveness and high sickness rate can still cause almost the entire population to be infected.
4. A low death rate can still cause a lot of death with a low recovery rate.

Overall, it was fascinating seeing the cellular automata work itself with each new parameter. It was slightly horrifying seeing the whole population turn black from high death rates or seeing a sea of green slowly turn yellow/black from a low vaccine effectiveness and informs a lot about how disease work and why it's so important to really advocate for vaccines.
