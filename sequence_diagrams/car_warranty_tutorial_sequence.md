<!--
This sequence diagram using Mermaid has been created
for instructional purposes. In addition to explaining
basic sequence diagram syntax, it introduces:

* Notes
* Loops
* Async calls

Explanations can be found in the comments, denoted by %%.

We bookend this file, starting with ```mermaid and ending with ```
to signify that this file uses Mermaid.
-->

```mermaid
%% Declaration of the diagram type
sequenceDiagram
    %% 'participant' boxes Robocall Company (both top and bottom of diagram)
    participant Robocall Company
    %% 'actor' creates a stick figure (both top and bottom of diagram)
    %% 'as Jared' is us creating an alias, which appears on the diagram
    actor J as Jared
    %% This is a note. You must specify where it appears.
    Note right of J: J is trying to live his best life
    actor R as Rhonda
    %% Signals the beginning of being 'active' in diagram
    activate Robocall Company
    activate J
    loop Every day
        Robocall Company->>J: 1. Calls about J's extended car warranty
        J-->>Robocall Company: 2. Responds he isn't interested
        Robocall Company->>J: 3. Reassures J they'll call back
        Note over J, Robocall Company: (Robocall kept their promise)
    end
    %% Signals end of being 'active' in diagram
    deactivate Robocall Company
    activate R
    J-)R: 4. Texts colleague to complain
```