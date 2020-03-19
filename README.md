# MultiEventWithoutPriorityManagement
MultiEventWithoutPriorityManagement
In the vehicle Hazard Warning Light control system, many operations will make the extorior light flashing.Such as, HazardWarning Switch(2Hz),Lock/Unlock indication,Antitheft indication,Emergency braking light,Autonomous Parking,,,,more than 20 events which were so different depending on differnt car configuration.each operation will cause a different flash frequency.when more than 2 events happens at the same time, the later happen one will get the final control that means flash frequency will be determained by this event.
suppose that we have 20 events, they will happen independently as input.we also have an output and we can get which event is running by read that output.
