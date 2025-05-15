Title: AI-EBPL – Autonomous Vehicles and Robotics 


Abstract 

The final phase of the AI-EBPL project integrates all previous developments into a fully 
functional prototype that demonstrates real-time decision-making in autonomous systems. 
Using a Stream lit-based interface, this phase presents a live simulation where users can upload 
sensor data and observe how the AI system interprets terrain, makes navigation decisions, and 
handles system safety checks. This phase includes system walkthroughs, technical 
documentation, testing feedback, performance metrics, and a roadmap for future 
improvements. 


1. Project Demonstration 

Overview: 

A live simulation platform was developed using Python and Stream lit to showcase AI
driven navigation based on proximity sensor data. This demonstration displays how the system 
classifies terrain risk, makes autonomous movement decisions, and responds to safety 
conditions.


Demonstration Highlights: 

• Interactive Simulation: Users upload .csv sensor data and observe real-time AI 
decisions. 

• Terrain Classification: The system classifies terrain into safe, caution, or danger based 
on distance.

• AI Navigation Decisions: The AI decides whether to move forward, slow down, or 
reroute. 

• Safety Monitoring: A simulated fault-detection mechanism halts the operation under 
risk. 

• User Interface: Built with Stream lit for ease of access and interactivity. 


Outcomes: 

• Demonstrated intelligent navigation logic. 

• Showcased live decision feedback for stakeholder understanding. 

• Established a visual interface to interact with the prototype.


2. Project Documentation
   
Overview: 

Complete documentation has been prepared for system components, including AI logic, 
interface, and data handling. 

Documentation Includes: 

• System Architecture: Flow of data from sensor upload to decision output. 

• Codebase Documentation: Detailed explanations of AI functions, decision logic, and 
safety monitoring. 

• User Guide: Instructions on how to upload files, run simulations, and interpret logs. 

• Administrator Manual: Guidelines on updating code, handling sensor formats, and 
system maintenance. 

• Testing Reports: Metrics from test cases measuring response accuracy, decision speed, 
and fault handling.


Outcomes: 

• Clear guidance for current users and future developers.

• Enables system scaling and easy debugging through documented logic and flow. 


4. Feedback and Final Adjustments

Overview: 

During prototype demonstrations, feedback was gathered from mentors and peers to refine 
the system. 
Feedback Actions:

• Issue: Decision logic too binary (safe/unsafe). 

Solution: Introduced caution level for better environmental awareness. 

• Issue: Fault detection was random and unrealistic. 

Solution: Added structure to safety triggers for future sensor-based diagnostics. 

• Issue: Simulation not fault-tolerant to missing data. 

Solution: Added error handling for invalid rows. 

• Issue: No visualization of logs. 

Solution: Logs now presented in a structured format, optionally downloadable. 

Final Testing: 

• Validated terrain classification logic. 

• Verified AI decision output correctness for multiple datasets. 

• Tested GUI responsiveness under various file inputs. 



6. Final Project Report Submission

Overview: 

The project report includes details from concept through to final implementation and 
testing. 

Sections: 

• Executive Summary: Purpose and significance of AI-EBPL. 

• Development Phases: Summary of each phase with key contributions. 

• Code Snippets: Representative sections of Python/Stream lit implementation. 

• Screenshots: GUI interface, sensor data table, decision logs. 

• Challenges & Solutions: Documentation of roadblocks and how they were overcome. 

• Outcomes: Verified performance in navigation logic and safe system operations. 

Outcome: 

A comprehensive report was prepared to encapsulate the system’s development, testing, 
and deployment readiness.


8. Project Handover and Future Works
   
Overview: 

The project is ready for further development or deployment in larger-scale robotics 
platforms.

Next Steps: 

• Reinforcement Learning Integration: For continuous learning and adaptability. 

• Live Map Visualization: Display AI navigation path over time. 

• Hardware Integration: Connect with real microcontrollers for physical testing. 

• Edge AI Deployment: Optimize model for low-power hardware. 


Outcome:

The system is handed over with future enhancements suggested, enabling academic 
continuation or practical deployment.
