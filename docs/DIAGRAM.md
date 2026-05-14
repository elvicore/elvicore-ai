+------------------------------------------------------+
|                  Application Context                 |
|  - User interaction                                  |
|  - Domain-specific logic                             |
+---------------------------+--------------------------+
                            |
                            v
+------------------------------------------------------+
|            Safety & Ethics Architecture              |
|  - Fixed, non-negotiable rules                       |
|  - Non-agentic behaviour constraints                 |
|  - Misuse and abuse prevention                       |
+---------------------------+--------------------------+
                            |
                            v
+------------------------------------------------------+
|           Scenario & Threat Modelling Layer          |
|  - Failure scenarios                                 |
|  - Misuse scenarios                                  |
|  - Social engineering & manipulation                 |
|  - Technical attack surfaces                         |
+---------------------------+--------------------------+
                            |
                            v
+------------------------------------------------------+
|            Zero-Trust & Policy Enforcement           |
|  - No implicit trust in AI                           |
|  - No runtime rule changes                           |
|  - Deterministic decision filters                    |
+---------------------------+--------------------------+
                            |
                            v
+------------------------------------------------------+
|           Hardware-Rooted Trust & Manifest           |
|  - Secure element / root of trust (conceptual)       |
|  - Signed security manifest                          |
|  - No boot without verified safety state             |
+---------------------------+--------------------------+
                            |
                            v
+------------------------------------------------------+
|                    AI Model Layer                    |
|  - Treated as a guest component                      |
|  - Bounded by outer architecture                     |
|  - No direct access to hardware or rules             |
+------------------------------------------------------+


Reading the diagram:

AI sits at the bottom, as a constrained component.

Hardware‑rooted trust + manifest define what is allowed.

Zero‑trust + enforcement ensure rules cannot be changed at runtime.

Scenario & threat modelling shapes the safety architecture.

Safety & ethics form the hard boundary for all behaviour.

Applications interact only through this layered safety stack.
