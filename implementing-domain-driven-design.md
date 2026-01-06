(In-Progress) Vaughn Vernon: Implementing Domain-Driven Design

---

## Main Themes

## DDD organizational and integration patterns

**Partnership**
→ Teams work as equals, jointly designing and evolving closely coupled models.

**Shared Kernel**
→ Teams share and jointly maintain a small, common part of the domain model.

**Customer-Supplier Development**
→ One team owns a system or model while another depends on it, influencing changes through clear requirements and ongoing feedback.

**Conformist**
→ One team fully adopts another team’s model and interfaces as they are, making no attempt to influence or change them.

**Anticorruption Layer**
→ A dedicated translation layer isolates a system from an external model by converting between internal concepts and outside interfaces.

**Open Host Service**
→ A system exposes a well-defined, stable interface that multiple external consumers can use consistently.

**Published Language**
→ A shared, well-documented language defines how systems exchange information, ensuring consistent meaning across boundaries.

**Separate Ways**
→ Two systems operate independently, with no integration or shared model between them.

**Big Ball of Mud**
→ A system lacks clear structure, with tangled, unorganized code and dependencies throughout.
