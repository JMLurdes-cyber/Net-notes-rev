| **Collapsed Core Architecture**                                                        | **Three Tiered Architecture**                                                             |
| -------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------- |
| Combines [[Core Layer\|Core]] and [[Distribution Layer\|Distribution]] layers into one | It has three distinct layers, [[Core Layer]], [[Distribution Layer]] and [[Access Layer]] |
| + Easier to design and support                                                         | -More complex architecture\| Harder design                                                |
| + Cheaper to implement, since two layers are set unto one                              | -More expensive to implement and maintain, each layer must be properly set-up             |
| -Harder to scale up                                                                    | +Easier to scale up                                                                       |
| - Not as resilient, combining two layers makes it have a bigger point of failure       | +The complexity allows for redundancy and resilience, in case of failure                  |
| Useful in smaller organizations                                                        | Useful in bigger organizations/organizations with a more complex system                   |

---
[[Network Architectures]]

