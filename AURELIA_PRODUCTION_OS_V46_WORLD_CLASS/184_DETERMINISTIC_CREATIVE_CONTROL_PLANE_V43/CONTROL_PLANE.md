# Control Plane

LOAD → FREEZE → QUERY → PLAN → REVIEW → COMPILE → VALIDATE → PROVE → PACKAGE。

FREEZE 后禁止隐式读取变化中的状态。任何输入变化产生新 context_hash。
