 # Analysis-of-open-loop-and-closed-loop-control-system
## Aim :
  To analyse the open loop and closed loop system having G(S)=1/(S^2+10S+20)  when an unit step input is applied using MATLAB.
## Apparatus Required:
  Computer with MATLAB software
## Theory
  ### Open loop control system
  In this system, the output doesn’t change the action of the control system. It doesn’t have any feedback. It is very simple, needs low maintenance, quick operation, and cost-effective. The accuracy of this system is low and less dependable.
  <img width="652" height="175" alt="image" src="https://github.com/user-attachments/assets/0a9d8129-eb64-40bb-8efd-434edcb2bd5a" />
 ### Closed loop control System
The closed-loop control system can be defined as the output of the system that depends on the input of the system. This control system has one or more feedback loops among its input & output. This system provides the required output by evaluating its input. This kind of system produces the error signal and it is the main disparity between the output and input of the system.
                     <img width="508" height="220" alt="image" src="https://github.com/user-attachments/assets/ad4b9b9e-bf06-4108-a4c0-5320be064b1f" />

Consider a system having plant G(S)=  1/(S^2+10S+20), H(S) = 1(negative unity feedback system) and Controller C(S) = 300.
C(S) and G(S) are in series, 300/(S^2+10S+20)
300/(S^2+10S+20) and H(S) are in negative feedback.
Therefore, Closed loop transfer function, (C(S))/(R(S))=300/(S^2+10S+320)
## Program: 
### Open loop System
<img width="614" height="577" alt="image" src="https://github.com/user-attachments/assets/cb5b4f36-ac4a-47d2-86d6-51ece053a8ee" />

### Closed loop System
<img width="542" height="589" alt="image" src="https://github.com/user-attachments/assets/7e62b42c-772d-4e1e-8feb-4589e720d942" />


## Simulink:
Open Loop System:
<img width="1786" height="739" alt="image" src="https://github.com/user-attachments/assets/8ae2b44e-c583-4a6d-971b-731c1158e549" />
Closed Loop System:
<img width="1774" height="764" alt="image" src="https://github.com/user-attachments/assets/270c0bdf-3b8f-4cfd-9351-99b03959f87d" />

## Procedure:
	Open MATLAB software
	Open a new script file.
	Type the program.
	Save and Execute the program.
	Analyse the result.
## Output:
### Open Loop System:

<img width="843" height="738" alt="image" src="https://github.com/user-attachments/assets/fb1edb12-27c2-493b-b48b-62bbaee0e508" />


### Closed Loop System:
<img width="844" height="751" alt="image" src="https://github.com/user-attachments/assets/afe4e27a-4570-4e5c-84ef-79e1f952d2fe" />

## Result:
Thus the open loop and closed loop system are analysed and the following conclusions are arrived.
### Open loop system
Steady State Error =0.95 <br>
Settling Time = 2.25
### Closed loop System
Steady State Error =0.04 <br>
Settling Time = 1.2





