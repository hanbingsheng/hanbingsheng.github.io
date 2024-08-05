---
date: 2023-12-20
published: true
title: "Sany Rotary Drilling Rig HMI Design"
description: "Central Control System Interface Design for Sany Rotary Drilling Rig"
categories: 
disciplines: Graphic, Slides, PPT
media: App
ownership: Personal
client:
time_period: 2022
thumbnail: "/projects/HMI-thumbnail.png"

intro: |
  The rotary drilling rig is a specialized heavy engineering machine used for driving deep foundations. As the heavy machinery industry evolves, there is a growing demand for intelligent features in these machines. This necessitates the development of a new human-machine interface (HMI) for the control screens to accommodate these advanced functionalities. Currently, the display interfaces in heavy machinery are outdated, offering poor visual and interaction experiences.

content_layout:

  - section_layout: text
    content: |
      <h2>Project Overview</h2>
      This project aims to address these challenges by designing a modern, user-friendly central control system interface for Sany Group's rotary drilling rigs. The objective is to enhance the user experience by integrating advanced functionalities and providing a visually appealing and efficient interface. This new interface will not only meet the current needs but also set a benchmark for future developments in the heavy machinery sector. The significance of this project lies in its potential to improve operational efficiency, safety, and overall user satisfaction in the use of rotary drilling rigs.
      <p>The current market rotary drilling rig control interfaces are as follows:</p>

  - section_layout: 1col-narrow
    images:
      - caption: 
        description: 
        url: '/projects/hmi-2.png'
        width: 
        height:
      
  - section_layout: text
    content: |
      <h2>Project Background</h2>
      Rotary drilling rigs require robust control systems for efficiency and safety. As the industry evolves, modern HMIs are essential to integrate intelligent features. Current interfaces are outdated and inefficient. This project aims to create a cutting-edge control system interface for Sany Group's rigs, enhancing user interaction, operational efficiency, and supporting advanced features.

  - section_layout: text
    content: |
      <h2>Design Requirements Analysis</h2>
      <h3>User and Market Requirements</h3>
      Our primary users are operators aged between 20 and 45. They generally possess a middle school level education, have undergone professional technical training, and have good driving skills. As the construction industry evolves, these users require advanced technological tools to aid in their work. Understanding their daily challenges and the environments they operate in is crucial for designing an interface that is both user-friendly and effective. Expanding on this, operators need interfaces that are intuitive and require minimal learning time, enabling them to focus more on the task at hand rather than grappling with complex UI.

  - section_layout: 1col-narrow
    images:
      - caption: 
        description: 
        url: '/projects/hmi-persona.png'
        width: 
        height:

  - section_layout: text
    content: |
      
      <h3>Design Objectives</h3>
      User Needs: Operators of heavy machinery like rotary drilling rigs often engage in long-duration tasks. They require frequent checks on display screens to understand the current operational status. The efficiency of information transmission on these screens is of paramount importance. Additionally, operators often interact with the screens while wearing gloves, necessitating an interface that is both clear and easy to use, ensuring safety and preventing accidental operations. For instance, clear visual cues and large touch targets are essential in avoiding errors during critical operations.
      
      Functionality and Development Needs: As we introduce new and advanced automation and intelligent features, our new development team must address the challenges posed by this new era. This also means the interface will frequently undergo changes, requiring a flexible design system that can accommodate new functionalities without compromising on usability. This involves designing modular UI components that can be easily updated or replaced as new features are developed.

      Therefore, our design principles are:

  - section_layout: 1col-narrow
    images:
      - caption: 
        description: 
        url: '/projects/hmi-goal.png'
        width: 
        height:

  - section_layout: text
    content: |     

      <h2>Design Process</h2>
      <h3>Choosing Visual Style</h3>
      We opted for a flat design style for several reasons. This design approach simplifies the visual elements, reducing clutter and making it easier for operators to quickly find and understand the information they need. A flat design also aligns well with modern UI/UX trends, providing a clean and professional look that enhances the overall user experience. This visual style is particularly advantageous in industrial contexts where clarity and quick comprehension are critical. By eliminating unnecessary visual noise, flat design ensures that essential information stands out, which is crucial during high-stress operations
      
  - section_layout: 1col-narrow
    images:
      - caption: 
        description: 
        url: '/projects/hmi-4-0.png'
        width: 
        height:

  - section_layout: text
    content: |          

      <h3>Building the Visual System</h3>
      <h4>Colors</h4>
      The color scheme was chosen to enhance readability and ensure that critical information stands out. We used contrasting colors for different operational statuses to make it easy for operators to differentiate between various states at a glance. For instance, operational alerts are displayed in red, normal status indicators in green, and warnings in yellow. This color-coding system helps in immediate recognition and appropriate response.

  - section_layout: 1col-narrow
    images:
      - caption: 
        description: 
        url: '/projects/hmi-colors.png'
        width: 
        height:

  - section_layout: text
    content: |          
      
      <h4>Icons</h4>
      Icons were designed to be easily recognizable and convey their meanings quickly. Given the lower resolution of the display hardware, we ensured the icons were clear and not overly detailed, which could make them hard to read. This interface is mounted on a 1024*768 display screen, which is a 4:3 display hardware, and compared with many high-resolution, high-PPI mobile terminal display screens, such a resolution rate is relatively low. This is the current standard for industrial equipment, emphasizing more practicality and robustness. These lower resolutions require us to make design adjustments to ensure classic icon shapes and convey standard operational symbols effectively. The goal was to create a set of icons that are both aesthetically pleasing and functional. Each icon underwent rigorous testing to ensure it communicated the intended message effectively, even under challenging visibility conditions. 

  - section_layout: 1col-narrow
    images:
      - caption: 
        description: 
        url: '/projects/hmi-icons.png'
        width: 
        height:

  - section_layout: text
    content: |    
      <h4>Typography</h4>
      Text elements were designed to be legible at a distance, considering the varying lighting conditions operators might encounter. We used a sans-serif font for its clarity and modern look, ensuring that all text is easy to read and understand. Additionally, font size and spacing were optimized to maintain readability in different working environments. This is especially important in the heavy machinery industry, where complex concepts often need to be conveyed succinctly. Ensuring readability and comprehensibility of text helps prevent misinterpretation and operational errors. (Refer to images below for examples)

  - section_layout: 1col-narrow
    images:
      - caption: 
        description: 
        url: '/projects/hmi-typo.png'
        width: 
        height:

  - section_layout: text
    content: | 
      <h3>Visualizing the Construction Process</h3>
      We detailed the working conditions of key components such as the drilling head and the pressure table, providing operators with real-time feedback on their actions. This level of detail helps operators make informed decisions and improves overall efficiency. Visual aids like animated diagrams and real-time status indicators are used to present the drilling process in an intuitive manner, reducing cognitive load and improving operational precision. (Expand based on the images below)

  - section_layout: video
    videos:
      - url: '/assets/videos/hmi-ani-1.mp4'

  - section_layout: text
    content: |
      In addition, the operational status of the pressure table is also visualized, showcasing the relationship between the pressure table and the drilling rod, the force application points, and the current status of the pressure table. This comprehensive visualization ensures operators have all the information they need to perform their tasks safely and effectively. Detailed overlays and interactive elements allow operators to delve deeper into specific aspects of the process, enhancing their understanding and control.

  - section_layout: 1col-narrow
    images:
      - caption: 
        description: 
        url: '/projects/hmi-3.png'
        width: 
        height:

  - section_layout: text
    content: |
      <h2>Interface Design</h2>
      The interface design for the rotary drilling rig display focused on creating a user-centered experience that meets the demands of modern construction machinery. Our approach involved several key steps to ensure the final design was both functional and aesthetically pleasing:

  - section_layout: 1col-10-centered
    images:
      - caption: Main Interface
        description: 
        url: '/projects/hmi-main-1.png'
        width: 
        height:

  - section_layout: 1col-10-centered
    images:
      - caption: Mast Adjustment Interface
        description: 
        url: '/projects/hmi-main-2.png'
        width: 
        height:

  - section_layout: 1col-10-centered
    images:
      - caption: Travel/Rotation Interface
        description: 
        url: '/projects/hmi-main-3.png'
        width: 
        height:

  - section_layout: 1col-10-centered
    images:
      - caption: Status Bar Notifications Interface
        description: 
        url: '/projects/hmi-status-1.png'
        width: 
        height:

  - section_layout: 1col-10-centered
    images:
      - caption: Status Bar Common Functions Interface
        description: 
        url: '/projects/hmi-status-2.png'
        width: 
        height:

  - section_layout: 1col-10-centered
    images:
      - caption: Auto Mast Adjustment Function Preview (Prototype Interface)
        description: 
        url: '/projects/test.gif'
        width: 
        height:

  - section_layout: text
    content: |
      <h2>Project Summary</h2>
      Reflecting on the design process for the central control system interface of Sany Group's rotary drilling rigs, we identified several key areas for improvement. Our research and hands-on testing revealed significant shortcomings in the existing control interfaces, particularly in terms of visual appeal and user interaction.

      <p>To address these issues, we developed a modern and user-friendly HMI that integrates advanced functionalities required by the evolving heavy machinery industry. The new design not only enhances the operational efficiency and safety of the rotary drilling rigs but also provides an intuitive and visually appealing experience for the operators. This project demonstrates the potential of well-designed interfaces in transforming the user experience and setting new standards in the heavy machinery sector.</p>

  - section_layout: 1col-narrow
    images:
      - caption: 
        description: 
        url: '/projects/hmi-end.png'
        width: 
        height:

---
