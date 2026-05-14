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
