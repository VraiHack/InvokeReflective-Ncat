# InvokeReflectiveNcat
During my training with eLearsecurity at the Advanced level, there was a littel bit complicated lab (LAB1) with the objective to Custom an Undetectable Macro (InvokeReflectiveNcat is the final objective)

**So this is not a copy past for the LAB!**
i decided it to make it easier for you (elearnsecurity students/...) by <span style="color: green"> desiging the attack in a schematic way </span>
<ins></ins> for more clarity for the steps

So, this is a simple designe to reflectively inject the NCAT.exe in the targe memory
- We can evade A/V by removing all comments and renaming/obfuscating functions from Invoke-ReflectivePEInjection code.
- And evading IDS by doing a XOR obfuscation/de-obfuscation for the attack’s stage payload.

![image](https://user-images.githubusercontent.com/26716241/132065528-3246c9f0-3e0a-451a-89fa-8fc43cdd13e1.png)
