## Project Timeline – Gantt Chart

```mermaid
gantt
    title CHARGER Card Project Gantt Chart
    dateFormat  YYYY-MM-DD
    axisFormat  %b %d

    section Phase 1 – Project Initialization
    Team Meeting #1                     :tm1, 2026-01-10, 1d
    KiCad Schematic & PCB Development   :p1, 2026-01-10, 2026-01-16
    Progress Report #1                  :pr1, 2026-01-16, 1d
    Updated Timeline Approved           :milestone, m1, 2026-01-16, 0d

    section Phase 2 – Design & Firmware Development
    Team Meeting #2                     :tm2, 2026-01-17, 1d
    Firmware Code V3 Development        :p2, 2026-01-17, 2026-02-06
    Firmware Code V3 Testing            :p3, 2026-01-17, 2026-02-06
    KiCad Schematic & PCB Refinement    :p4, 2026-01-17, 2026-02-06
    Component Research                  :p5, 2026-01-17, 2026-02-06
    Project Proposal Submission         :pr2, 2026-01-23, 1d
    Final KiCad Schematic Completed     :milestone, m2, 2026-02-06, 0d
    Final PCB Layout Completed          :milestone, m3, 2026-02-06, 0d
    Progress Report #2                  :pr3, 2026-02-06, 1d

    section Phase 3 – Fabrication Preparation
    Team Meeting #3                     :tm3, 2026-02-07, 1d
    Firmware Code V3 Finalization       :p6, 2026-02-06, 2026-02-13
    Firmware Code V3 Validation         :p7, 2026-02-06, 2026-02-13
    Final Component Selection           :p8, 2026-02-06, 2026-02-13
    All Components Ordered              :milestone, m4, 2026-02-13, 0d
    Firmware Code V3 Completed          :milestone, m5, 2026-02-13, 0d
    First Board Run                     :milestone, m6, 2026-02-13, 0d
    Progress Report #3                  :pr4, 2026-02-13, 1d

    section Phase 4 – Prototype Expansion
    Team Meeting #4                     :tm4, 2026-02-14, 1d
    Soldering Method Research           :p9, 2026-02-14, 2026-02-20
    Additional Firmware V1 Development  :p10, 2026-02-14, 2026-02-20
    Proof-of-Concept Firmware V1        :milestone, m7, 2026-02-20, 0d
    Progress Report #4                  :pr5, 2026-02-20, 1d

    section Phase 5 – System Integration
    Team Meeting #5                     :tm5, 2026-02-21, 1d
    PCB Assembly & Soldering            :p11, 2026-02-20, 2026-03-20
    Hardware Integration Testing        :p12, 2026-02-20, 2026-03-20
    Firmware V2 Development             :p13, 2026-02-20, 2026-03-20
    CHARGER Card Hardware Complete      :milestone, m8, 2026-03-20, 0d
    Software Integration Complete       :milestone, m10, 2026-03-20, 0d
    CHARGER Card V1 Fully Functional    :milestone, m11, 2026-03-20, 0d
    Progress Report #5                  :pr6, 2026-03-20, 1d

    section Phase 6 – Refinement & Documentation
    Team Meeting #6                     :tm6, 2026-03-21, 1d
    Documentation Development           :p14, 2026-03-21, 2026-03-27
    System Debugging                    :p15, 2026-03-21, 2026-03-27
    Firmware V2 Finalization            :p16, 2026-03-21, 2026-03-27
    Firmware V2 Completed               :milestone, m13, 2026-03-27, 0d

    section Phase 7 – Final Design Review
    Team Meeting #7                     :tm7, 2026-03-28, 1d
    Final Firmware Development          :p17, 2026-03-28, 2026-05-01
    Final System Debugging              :p18, 2026-03-28, 2026-05-01
    Final Documentation                :p19, 2026-03-28, 2026-05-01
    Final Design Review                 :milestone, m14, 2026-04-10, 0d
    All Firmware Finalized              :milestone, m15, 2026-05-01, 0d
    Project Debugging Complete          :milestone, m16, 2026-05-01, 0d
    Documentation Complete              :milestone, m17, 2026-05-01, 0d
