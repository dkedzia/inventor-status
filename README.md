# Inventor Nastran Analysis Status


### Legend
✅ - Less than 1 fail for 100 attempts  
⚡ - Almost works. 1 - 20 fails for 100 attempts  
⭕ - Barely works. 21 - 99 fails for 100 attempts  
❌ - Doesn't work.  
⛔ - Doesn't apply.

## Summary

|      Action       | Keyboard script | .NET API | GPT model | Python script |  Status  |
|:-----------------:|:---------------:|:--------:|:---------:|:-------------:|:--------:|
| Switch to Nastran |    &#x26D4;     | &#x2705; | &#x26D4;  |   &#x26D4;    | &#x2705; |

## Gravity

|               Action                | Keyboard script | .NET API  |      GPT model       |     Python script     |  Status  |
|:-----------------------------------:|:---------------:|:---------:|:--------------------:|:---------------------:|:--------:|
|       New analysis initiator        |    &#x26D4;     | &#x26D4;  | gpt-4-vision-preview |    new-analysis.py    | &#x2705; |
|       New analysis name type        |    &#x2705;     | &#x26D4;  |       &#x26D4;       |       &#x26D4;        | &#x2705; |
|  Unit system select open/activate   |    &#x2705;     | &#x26D4;  |       &#x26D4;       |       &#x26D4;        | &#x2705; |
|  Unit system select option/confirm  |    &#x2705;     | &#x26D4;  |       &#x26D4;       |       &#x26D4;        | &#x2705; |
|        Unit window Ok/close         |    &#x2705;     | &#x26D4;  |       &#x26D4;       |       &#x26D4;        | &#x2705; |
|           Nodal selection           |    &#x2705;     | &#x26D4;  |       &#x26D4;       |       &#x26D4;        | &#x2705; |
|        Output Sets selection        |    &#x2705;     | &#x26D4;  |       &#x26D4;       |       &#x26D4;        | &#x2705; |
|     New analysis confirm/close      |    &#x2705;     | &#x26D4;  |       &#x26D4;       |       &#x26D4;        | &#x2705; |
|      New constrains initiator       |    &#x26D4;     | &#x26D4;  | gpt-4-vision-preview |   new-constrains.py   | &#x2705; |
|       Constrains/fixed button       |    &#x26D4;     | &#x26D4;  | gpt-4-vision-preview |   new-constrains.py   | &#x26A1; |
|        Constrains/Change POV        |    &#x26D4;     | &#x2705;  |       &#x26D4;       |       &#x26D4;        | &#x2705; |
|      Constrains/Pillars click       |    &#x26D4;     | &#x26D4;  | gpt-4-vision-preview | constrains-pillars.py | &#x2B55; |
|         Constrains/Ok click         |    &#x26D4;     | &#x26D4;  | gpt-4-vision-preview | constrains-confirm.py | &#x2705; |
|        Contacts/Auto button         |    &#x26D4;     | &#x26D4;  | gpt-4-vision-preview |      contacts.py      | &#x2705; |
| Contacts/Process finished detection |    &#x26D4;     | &#x26D4;  | gpt-4-vision-preview |      contacts.py      | &#x26A1; |
|           Loads initiator           |    &#x26D4;     | &#x26D4;  | gpt-4-vision-preview |       loads.py        | &#x2705; |
|            Loads/Set Fy             |    &#x2705;     | &#x26D4;  |       &#x26D4;       |       &#x26D4;        | &#x2705; |
|        Loads/Choose Gravity         |    &#x2705;     | &#x26D4;  |       &#x26D4;       |       &#x26D4;        | &#x2705; |
|           Loads/Ok click            |    &#x2705;     | &#x26D4;  |       &#x26D4;       |       &#x26D4;        | &#x2705; |
|       Idealizations initiator       |    &#x26D4;     | &#x26D4;  | gpt-4-vision-preview |   idealizations.py    | &#x2705; |
|       Idealizations/Ok click        |    &#x2705;     | &#x26D4;  |       &#x26D4;       |       &#x26D4;        | &#x2705; |
|       Generate mesh initiator       |    &#x26D4;     | &#x26D4;  | gpt-4-vision-preview |   generate-mesh.py    | &#x2705; |
|       Run Analysis initiator        |    &#x26D4;     | &#x26D4;  | gpt-4-vision-preview |    run-analysis.py    | &#x2705; |

## Spectrum

|                 Action                 | Keyboard script | .NET API  |      GPT model       |           Python script           |  Status  |
|:--------------------------------------:|:---------------:|:---------:|:--------------------:|:---------------------------------:|:--------:|
|         New analysis initiator         |    &#x26D4;     | &#x26D4;  | gpt-4-vision-preview |          new-analysis.py          | &#x2705; |
|         New analysis name type         |    &#x2705;     | &#x26D4;  |       &#x26D4;       |             &#x26D4;              | &#x2705; |
|        New analysis type change        |    &#x2705;     | &#x26D4;  |       &#x26D4;       |             &#x26D4;              | &#x2705; |
|    Unit system select open/activate    |    &#x2705;     | &#x26D4;  |       &#x26D4;       |             &#x26D4;              | &#x2705; |
|   Unit system select option/confirm    |    &#x2705;     | &#x26D4;  |       &#x26D4;       |             &#x26D4;              | &#x2705; |
|          Unit window Ok/close          |    &#x2705;     | &#x26D4;  |       &#x26D4;       |             &#x26D4;              | &#x2705; |
|            Nodal selection             |    &#x2705;     | &#x26D4;  |       &#x26D4;       |             &#x26D4;              | &#x2705; |
|         Output Sets selection          |    &#x2705;     | &#x26D4;  |       &#x26D4;       |             &#x26D4;              | &#x2705; |
|       New analysis confirm/close       |    &#x2705;     | &#x26D4;  |       &#x26D4;       |             &#x26D4;              | &#x2705; |
|        Idealizations initiator         |    &#x26D4;     | &#x26D4;  | gpt-4-vision-preview |         idealizations.py          | &#x2705; |
|         Idealizations/Ok click         |    &#x2705;     | &#x26D4;  |       &#x26D4;       |             &#x26D4;              | &#x2705; |
|        Mesh settings initiator         |    &#x26D4;     | &#x26D4;  | gpt-4-vision-preview |         mesh-settings.py          | &#x2705; |
|     Mesh settings/continue meshing     |    &#x26D4;     | &#x26D4;  | gpt-4-vision-preview |         mesh-settings.py          | &#x26A1; |
|      Mesh settings/generate mesh       |    &#x2705;     | &#x26D4;  |       &#x26D4;       |             &#x26D4;              | &#x2705; |
|         Mesh settings/Ok click         |    &#x2705;     | &#x26D4;  |       &#x26D4;       |             &#x26D4;              | &#x2705; |
|        New constrains initiator        |    &#x26D4;     | &#x26D4;  | gpt-4-vision-preview |         new-constrains.py         | &#x2705; |
|        Constrains/fixed button         |    &#x26D4;     | &#x26D4;  | gpt-4-vision-preview |         new-constrains.py         | &#x26A1; |
|         Constrains/change type         |    &#x2705;     | &#x26D4;  |       &#x26D4;       |             &#x26D4;              | &#x2705; |
|          Constrains/Tx click           |    &#x26D4;     | &#x26D4;  | gpt-4-vision-preview |     constrains-spectrum-tx.py     | &#x2B55; |
|        Constrains/Pillars click        |    &#x26D4;     | &#x26D4;  | gpt-4-vision-preview |       constrains-pillars.py       | &#x2B55; |
|          Constrains/Ok click           |    &#x26D4;     | &#x26D4;  | gpt-4-vision-preview |       constrains-confirm.py       | &#x2705; |
|           Damping initiator            |    &#x26D4;     | &#x26D4;  | gpt-4-vision-preview |            damping.py             | &#x2705; |
|       Damping/Window activation        |    &#x26D4;     | &#x26D4;  | gpt-4-vision-preview |            damping.py             | &#x2705; |
|          Damping/value typing          |    &#x2705;     | &#x26D4;  |       &#x26D4;       |             &#x26D4;              | &#x2705; |
|          Damping/close window          |    &#x2705;     | &#x26D4;  |       &#x26D4;       |             &#x26D4;              | &#x2705; |
|        Dynamics setup initiator        |    &#x26D4;     | &#x26D4;  | gpt-4-vision-preview |         dynamics-setup.py         | &#x2705; |
|  Dynamics setup/Define or edit table   |    &#x26D4;     | &#x26D4;  | gpt-4-vision-preview |         dynamics-setup.py         | &#x2B55; |
|  Dynamics setup/Type select activator  |    &#x26D4;     | &#x26D4;  | gpt-4-vision-preview |         dynamics-setup.py         | &#x2705; |
|      Dynamics setup/Select option      |    &#x2705;     | &#x26D4;  |       &#x26D4;       |             &#x26D4;              | &#x2705; |
| Dynamics setup/Damping value activator |    &#x26D4;     | &#x26D4;  | gpt-4-vision-preview |  dynamics-setup-dumping-value.py  | &#x2705; |
|   Dynamics setup/Enter damping value   |    &#x2705;     | &#x26D4;  |       &#x26D4;       |             &#x26D4;              | &#x2705; |
|     Dynamics setup/Table activator     |    &#x26D4;     | &#x26D4;  | gpt-4-vision-preview | dynamics-setup-table-activator.py | &#x2B55; |
|      Dynamics setup/Data entrance      |    &#x2705;     | &#x26D4;  |       &#x26D4;       |             &#x26D4;              | &#x2705; |
|         Dynamics setup/Confirm         |    &#x26D4;     | &#x26D4;  | gpt-4-vision-preview |     dynamics-setup-confirm.py     | &#x2705; |
|          Dynamics setup/Close          |    &#x2705;     | &#x26D4;  |       &#x26D4;       |             &#x26D4;              | &#x2705; |
|          Contacts/Auto button          |    &#x26D4;     | &#x26D4;  | gpt-4-vision-preview |            contacts.py            | &#x2705; |
|  Contacts/Process finished detection   |    &#x26D4;     | &#x26D4;  | gpt-4-vision-preview |            contacts.py            | &#x26A1; |
|             Spectrum copy              |    &#x26D4;     | &#x26D4;  | gpt-4-vision-preview |         spectrum-copy.py          | &#x26A1; |
|        Spectrum copies renaming        |    &#x26D4;     | &#x26D4;  | gpt-4-vision-preview |      spectrum-copy-setup.py       | &#x26A1; |
|         Run Analysis initiator         |    &#x26D4;     | &#x26D4;  | gpt-4-vision-preview |          run-analysis.py          | &#x2705; |

## Wind

|               Action                | Keyboard script | .NET API  |      GPT model       |     Python script     |  Status  |
|:-----------------------------------:|:---------------:|:---------:|:--------------------:|:---------------------:|:--------:|
|       New analysis initiator        |    &#x26D4;     | &#x26D4;  | gpt-4-vision-preview |    new-analysis.py    | &#x2705; |
|       New analysis name type        |    &#x2705;     | &#x26D4;  |       &#x26D4;       |       &#x26D4;        | &#x2705; |
|  Unit system select open/activate   |    &#x2705;     | &#x26D4;  |       &#x26D4;       |       &#x26D4;        | &#x2705; |
|  Unit system select option/confirm  |    &#x2705;     | &#x26D4;  |       &#x26D4;       |       &#x26D4;        | &#x2705; |
|        Unit window Ok/close         |    &#x2705;     | &#x26D4;  |       &#x26D4;       |       &#x26D4;        | &#x2705; |
|           Nodal selection           |    &#x2705;     | &#x26D4;  |       &#x26D4;       |       &#x26D4;        | &#x2705; |
|        Output Sets selection        |    &#x2705;     | &#x26D4;  |       &#x26D4;       |       &#x26D4;        | &#x2705; |
|     New analysis confirm/close      |    &#x2705;     | &#x26D4;  |       &#x26D4;       |       &#x26D4;        | &#x2705; |
|      New constrains initiator       |    &#x26D4;     | &#x26D4;  | gpt-4-vision-preview |   new-constrains.py   | &#x2705; |
|       Constrains/fixed button       |    &#x26D4;     | &#x26D4;  | gpt-4-vision-preview |   new-constrains.py   | &#x26A1; |
|        Constrains/Change POV        |    &#x26D4;     | &#x2705;  |       &#x26D4;       |       &#x26D4;        | &#x2705; |
|      Constrains/Pillars click       |    &#x26D4;     | &#x26D4;  | gpt-4-vision-preview | constrains-pillars.py | &#x2B55; |
|         Constrains/Ok click         |    &#x26D4;     | &#x26D4;  | gpt-4-vision-preview | constrains-confirm.py | &#x2705; |
|        Contacts/Auto button         |    &#x26D4;     | &#x26D4;  | gpt-4-vision-preview |      contacts.py      | &#x2705; |
| Contacts/Process finished detection |    &#x26D4;     | &#x26D4;  | gpt-4-vision-preview |      contacts.py      | &#x26A1; |
|       Idealizations initiator       |    &#x26D4;     | &#x26D4;  | gpt-4-vision-preview |   idealizations.py    | &#x2705; |
|       Idealizations/Ok click        |    &#x2705;     | &#x26D4;  |       &#x26D4;       |       &#x26D4;        | &#x2705; |
|           Loads initiator           |    &#x26D4;     | &#x26D4;  | gpt-4-vision-preview |       loads.py        | &#x2705; |
|        Loads/Choose Pressure        |    &#x2705;     | &#x26D4;  |       &#x26D4;       |       &#x26D4;        | &#x2705; |
|      Loads/Magnitude activator      |    &#x26D4;     | &#x26D4;  | gpt-4-vision-preview |  loads-magnitude.py   | &#x2705; |
|         Loads/Type pressure         |    &#x2705;     | &#x26D4;  |       &#x26D4;       |       &#x26D4;        | &#x2705; |
|          Loads/Change POV           |    &#x26D4;     | &#x2705;  |       &#x26D4;       |       &#x26D4;        | &#x2705; |
|      Loads/Elements selection       |    &#x26D4;     | &#x26D4;  | gpt-4-vision-preview |  loads-selection.py   | &#x2B55; |
|           Loads/Ok click            |    &#x2705;     | &#x26D4;  |       &#x26D4;       |       &#x26D4;        | &#x2705; |
|       Generate mesh initiator       |    &#x26D4;     | &#x26D4;  | gpt-4-vision-preview |   generate-mesh.py    | &#x2705; |
|       Run Analysis initiator        |    &#x26D4;     | &#x26D4;  | gpt-4-vision-preview |    run-analysis.py    | &#x2705; |