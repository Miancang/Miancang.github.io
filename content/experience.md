---
# Leave the homepage title empty to use the widget title
title: 'Experience'
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: '6rem'

sections:
  # 添加目录导航栏
  - block: markdown
    id: toc
    content:
      title: ''
      text: |-
        <div style="background: #f8f9fa; padding: 20px; border-radius: 10px; margin-bottom: 30px;">
        <h3>Contents</h3>
        <ul style="list-style: none; padding-left: 0;">
        <li><a href="#education" style="text-decoration: none; color: #007bff;">📚 Education</a></li>
        <li><a href="#seminar-talks" style="text-decoration: none; color: #007bff;">🎤 Seminar Talks</a></li>
        <li><a href="#conferences" style="text-decoration: none; color: #007bff;">🏛️ Conferences & Summer Schools</a></li>
        <li><a href="#internship" style="text-decoration: none; color: #007bff;">💼 Internship</a></li>
        <li><a href="#awards" style="text-decoration: none; color: #007bff;">🏆 Honors and Awards</a></li>
        <li><a href="#skills" style="text-decoration: none; color: #007bff;">⚡ Skills</a></li>
        </ul>
        </div>

  # Education Section
  - block: resume-education
    id: education
    content:
      title: Education
      items:
        - area: M.S. in Mathematics
          institution: University of Wisconsin--Madison
          location: Madison, WI, USA
          date_start: '2025-08-01'
          date_end: ''
          summary: |
            Current graduate student in Mathematics Department.
        
        - area: B.S. in Mathematics and Applied Mathematics (Zhiyuan Honors Program)
          institution: Shanghai Jiao Tong University
          location: Shanghai, China
          date_start: '2021-09-01'
          date_end: '2025-06-01'
          summary: |
            Graduated from the prestigious Zhiyuan Honors Program.

        # Exchange Programs
        - area: Visiting International Student Program (VISP)
          institution: University of Wisconsin--Madison
          location: Madison, WI, USA
          date_start: '2024-09-01'
          date_end: '2025-05-01'
          summary: |
            Exchange program in advanced mathematics.

  # Seminar Talks Section
  - block: resume-experience
    id: seminar-talks
    content:
      title: Seminar Talks
      items:
        - title: BBDG Decomposition
          company: University of Wisconsin--Madison
          location: Intersection Homology Reading Seminar
          date_start: ''
          date_end: ''
          summary: |
            [Seminar Link](https://wiki.math.wisc.edu/index.php/Intersection_Homology_Reading_Seminar)
        
        - title: Serre Spectral Sequence-I, II, III & Adams Spectral Sequence-I
          company: University of Wisconsin--Madison  
          location: Spectral Sequence in Algebraic Topology Reading Seminar (Organizer)
          date_start: '2024-09-24'
          date_end: ''
          summary: |
            [Seminar Link](https://wiki.math.wisc.edu/index.php/Spectral_Sequence_in_Algebraic_Topology_Reading_Seminar)
        
        - title: Sheaf Theory & Properties of Schemes & Homological Algebra
          company: University of Wisconsin--Madison
          location: Algebraic Geometry Reading Seminar
          date_start: '2024-09-01'
          date_end: '2024-11-15'
          summary: |
            Advanced topics in algebraic geometry.
        
        - title: Topology of Profinite Groups
          company: Shanghai Jiao Tong University
          location: Topic Course IV
          date_start: '2024-05-13'
          date_end: '2024-05-13'
          summary: |
            
        - title: Characteristic Classes and Vector Bundles
          company: Shanghai Jiao Tong University
          location: Topic Course III
          date_start: '2023-12-15'
          date_end: '2023-12-15'
          summary: |
            
        - title: Reinforcement Learning
          company: Shanghai Jiao Tong University
          location: Topic Course II
          date_start: '2023-04-07'
          date_end: '2023-04-07'
          summary: |
            
        - title: Non-standard Analysis
          company: Shanghai Jiao Tong University
          location: Topic Course I
          date_start: '2022-12-05'
          date_end: '2022-12-05'
          summary: |

  # Conferences Section
  - block: resume-experience
    id: conferences
    content:
      title: Conferences & Summer Schools Attended
      items:
        - title: Equivariant, Motivic, and Physical Topology in the Midwest
          company: Minnesota, USA
          location: Developments in equivariant and motivic homotopy theory
          date_start: '2025-10-24'
          date_end: '2025-10-26'
          summary: |
            
        - title: International Workshop on Algebraic Topology 2025
          company: Hangzhou, China
          location: Computations with the Adams Spectral Sequence and the Last Kervaire Invariant Problem
          date_start: '2025-07-01'
          date_end: '2025-07-05'
          summary: |
            
        - title: International Workshop on Algebraic Topology 2024
          company: Shanghai, China
          location: Motivic Stable Homotopy Theory
          date_start: '2024-06-23'
          date_end: '2024-06-27'
          summary: |
            
        - title: AI for Mathematics (Winter Training Program 2023-2024)
          company: Beijing, China
          location: Mathematical Formalization and Theorem Proving
          date_start: '2024-01-15'
          date_end: '2024-01-26'
          summary: |
            
        - title: ∞-type Café Summer School 2023
          company: Online
          location: Type Theory
          date_start: '2023-07-02'
          date_end: '2023-07-15'
          summary: |
            [Link](https://infinity-type-cafe.github.io/ntype-cafe-summer-school/)
            
        - title: Fudan Logic Summer School 2023
          company: Shanghai, China
          location: Model Theory of Nonabelian Free Groups & Nonstandard Analysis and Combinatorial Number Theory
          date_start: '2023-07-31'
          date_end: '2023-08-11'
          summary: |

  # Internship Section
  - block: resume-experience
    id: internship
    content:
      title: Internships
      items:
        - title: AI for Mathematics Internship Program
          company: Beijing International Center for Mathematical Research
          location: Beijing, China
          date_start: '2025-08-05'
          date_end: '2025-09-22'
          summary: |
            Formal data annotation in abstract algebra.

  # Awards Section
  - block: resume-awards
    id: awards
    content:
      title: Honors and Awards
      items:
        - title: Outstanding Undergraduate Scholarship
          url: ''
          date: '2024-12-01'
          awarder: Shanghai Jiao Tong University
          icon: ''
          summary: |
            
        - title: Zhiyuan Honors Scholarship
          url: ''
          date: '2024-11-01'
          awarder: Shanghai Jiao Tong University
          icon: ''
          summary: |
            
        - title: Zhiyuan Honors Scholarship
          url: ''
          date: '2023-11-01'
          awarder: Shanghai Jiao Tong University
          icon: ''
          summary: |
            
        - title: Zhiyuan Honors Scholarship
          url: ''
          date: '2022-11-01'
          awarder: Shanghai Jiao Tong University
          icon: ''
          summary: |
            
        - title: Zhiyuan Honors Scholarship
          url: ''
          date: '2021-11-01'
          awarder: Shanghai Jiao Tong University
          icon: ''
          summary: |

  # Skills Section
  - block: markdown
    id: skills
    content:
      title: Skills
      text: |-
        **Languages:** Mandarin Chinese (Native), English (Fluent)
        
        **Programming:** LaTeX, Lean
        
        **Development:** Git
---
