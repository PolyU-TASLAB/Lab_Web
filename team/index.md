---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

<!-- Include a large landscape photo below the TEAM title -->

<div style="text-align: center; margin-bottom: 20px;">
  <img src="https://github.com/PolyU-TASLAB/polyu-taslab.github.io/raw/main/images/team/team.jpg" alt="Team Banner" 
       style="width: 100%; height: auto; object-fit: cover; max-width: 850px; margin: 0 auto; border-radius: 15px;">
</div>

#### Faculty (Principal Investigator)
{% include list_pi.html data="members" component="portrait_pi" filters="role == 'pi'"  %}
#### Postdoctoral Fellows
{% include list_students.html data="members" component="portrait_students" filters="role == 'postdoc'" %}
#### Ph.D. Students
{% include list_students.html data="members" component="portrait_students" filters="role == 'phd'" %}
#### M.S./MPhil Students
{% include list_students.html data="members" component="portrait_students" filters="role == 'ms'" %}
#### Research/Project Assistant
{% include list_students.html data="members" component="portrait_students" filters="role == 'ra'" %}
#### Undergraduate Students
{% include list_students.html data="members" component="portrait_students" filters="role == 'under'" %}
#### Visiting Scholar/Students
{% include list_students.html data="members" component="portrait_students" filters="role == 'visiting'" %}
#### Alumni

