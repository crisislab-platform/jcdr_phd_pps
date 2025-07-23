---
layout: page
title: Students
permalink: /students/
---

# JCDR PhD Students

Our PhD students represent the next generation of disaster risk reduction researchers. They come from diverse academic backgrounds and bring fresh perspectives to critical challenges in hazard science, risk assessment, and community resilience.

## Current Students

<div class="students-grid">
  {% for student in site.students %}
    <div class="student-card">
      <div class="student-image">
        {% if student.image %}
          <img src="{{ student.image | relative_url }}" alt="{{ student.name }}">
        {% else %}
          <div class="placeholder-image">
            <i class="fas fa-user-graduate"></i>
          </div>
        {% endif %}
      </div>
      <div class="student-info">
        <h3><a href="{{ student.url | relative_url }}">{{ student.name }}</a></h3>
        <p class="research-area">{{ student.research_area }}</p>
        <p class="supervisor">Supervisor: {{ student.supervisor }}</p>
        <div class="year-badge">{{ student.year }}</div>
      </div>
    </div>
  {% endfor %}
</div>

## Research Diversity

Our students work across a broad spectrum of disaster-related topics:

### Natural Hazards Science
- Earthquake engineering and seismology
- Volcanic processes and hazard assessment
- Tsunami modeling and coastal dynamics
- Landslide mechanics and risk assessment
- Hydrological hazards and flooding

### Social Sciences and Humanities
- Community vulnerability and resilience
- Risk perception and communication
- Indigenous knowledge systems
- Post-disaster recovery processes
- Environmental justice and equity

### Technology and Innovation
- Remote sensing applications
- Machine learning for hazard assessment
- Geographic information systems
- Early warning systems
- Decision support tools

### Policy and Governance
- Disaster risk governance
- Emergency management planning
- Climate adaptation policy
- International development
- Risk regulation and compliance

## Student Support and Development

### Academic Excellence
- World-class supervision from JCDR and partner institutions
- Access to state-of-the-art research facilities
- Interdisciplinary training opportunities
- International conference presentation support

### Professional Development
- Research methodology workshops
- Academic writing and communication training
- Grant writing and proposal development
- Ethics and integrity in research training
- Career development planning

### Networking and Collaboration
- Regular research seminars and presentations
- Student-led research groups and discussions
- International research exchange opportunities
- Industry and practitioner engagement events
- Alumni network connections

### Funding and Scholarships
- Various scholarship opportunities available
- Research and travel funding support
- Teaching assistantship opportunities
- Industry partnership funding

## Application Information

### Entry Requirements
- Master's degree in relevant field (or equivalent)
- Strong academic record
- Research proposal aligned with JCDR themes
- English language proficiency
- References from academic supervisors

### Application Process
1. Initial contact with potential supervisors
2. Development of research proposal
3. Formal application submission
4. Interview process
5. Scholarship application (if applicable)

### Application Deadlines
- **Main Round:** December 1st (for following year admission)
- **Mid-Year Entry:** June 1st (limited places)

For detailed application information, visit the [Massey University Graduate Research School](https://www.massey.ac.nz/study/graduate-research-school/) website.

## Alumni Success

Our graduates have gone on to successful careers in:
- Academic research positions at leading universities
- Government agencies and policy roles
- International organizations (UN, World Bank, etc.)
- Consulting and private sector positions
- NGOs and community organizations

## Contact for Prospective Students

Interested in joining our program? Contact:

**Dr. Julia Becker**  
PhD Programme Coordinator  
Email: j.becker@massey.ac.nz  
Phone: +64 6 356 9099 ext. 83619

**Administrative Support**  
JCDR Administration  
Email: jcdr@massey.ac.nz
