# Legacy Account Modernization
<h1>Active Directory Lab - Legacy Account Modernization</h1>

<h2>Description</h2>

In this Project, we will go about **Securing Our Digital Front Door** to maintain the integrity of the enviorment.

Why is this neccessary? Think of our company's digital systems, our data, our applications, our financial records as an highly secure office building.

Our current identity and access system, which controls the 'keys' to this building, thus for the safety and integrity of this building we have to update the keys and locks. This need is very common amongst large organizations for a variety of reasons:
<ul> <li> Employee Growth - When Sarah from Marketing gets promoted to Finance, her old marketing access isn't automatically removed. 
She accumulates access over time, which is a security risk and a compliance problem, called "Access Creep"</ul>
Promotions Create Hidden Security Risk. Consider when Sarah moves from Marketing to Finance. In our current system, her marketing access remains active. This creates a dangerous accumulation of permissions over time, known as 'Access Creep. While Sarah herself is trustworthy, this outdated access becomes a liability. In the event her credentials are stolen, a malicious actor gains a wider foothold with permissions that look legitimate because they're so old. This makes detection harder and turns a simple promotion into a lingering security gap. 

To start we will set the paramater for accounts not recently signed into.

To balance the workload with the other teams it will be rolled out it phases.

Week 1: Reset for users inactive for 120+ days

Week 2: Reset for users inactive for 90+ days

Week 3: Reset for users inactive for 60+ days

Week 4: Reset for users inactive for 30+ days

This spreads the load for help desk, SOC, (etc) and allows for the process to be refined as the modernization continues.

<h1>Preventing This issue from reoccuring </h1>
For future prevention a life cycle policy should be created that automatically implements a flag on accounts that go 45 days without activity. 

<h2>Utilities Used</h2>

- <b>Active Directory</b> 
- <b>Powershell</b> 

<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)


