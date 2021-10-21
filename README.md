# InvokeReflective-Ncat
During my training with eLearsecurity at the Advanced level, there was a little bit complicated lab (LAB1) with the objective to Custom an Undetectable Macro (InvokeReflectiveNcat is the final objective)

**So this is not a copy past for the LAB and not even the final code!**
i just decided it to make it easier for you (elearnsecurity students/interested peoples in cyber) by:
```diff
- designing the creation phase of the Undetectable Macro in a schematic way
+ and for more clarity for the steps
```
So, this is a simple designe to reflectively inject the NCAT in the targe memory and compromise the target via a bind shell
- We can evade A/V by removing all comments and renaming/obfuscating functions from Invoke-ReflectivePEInjection code.
- And evading IDS by doing a XOR obfuscation/de-obfuscation for the attack’s stage payload.

![image](https://user-images.githubusercontent.com/26716241/138367740-e1377682-3323-4a6f-bfb5-be69d60560d6.png)
