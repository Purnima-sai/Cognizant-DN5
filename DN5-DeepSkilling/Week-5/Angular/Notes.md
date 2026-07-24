Student Course Portal - Phase 1: Core Fundamentals & Forms
This phase focuses on setting up the Angular 20 environment, building the foundational UI, and implementing robust user input handling through both Template-Driven and Reactive forms.


Hands-On 01: Environment & Architecture
Setup: Scaffolded the project using Angular CLI v20 with Standalone component defaults.
Structure: Explored the modern project structure, focusing on app.config.ts (replacing the traditional app.module.ts) and main.ts as the entry point.
Components: Built the initial shell including a Navigation Header, Dashboard (Home), and Course Listing pages.


Hands-On 02: Dynamic Data & Communication
Data Binding: Implemented all four types:
Interpolation: Displaying dynamic portal names.
Property Binding: Managing button states.
Event Binding: Handling clicks.
Two-Way Binding: Using [(ngModel)] for search inputs.
Lifecycle Hooks: Used ngOnInit for initialization and ngOnDestroy for cleanup to prevent memory leaks.
Parent-Child Flow: Established communication using @Input() to pass course data down to cards and @Output() with EventEmitter to bubble enrollment requests back up.


Hands-On 03: Directives & Custom Pipes
Structural Directives: Used *ngIf for loading states and *ngFor with trackBy (critical for DOM performance).
Attribute Directives: Applied dynamic styling via [ngClass] and [ngStyle].
Custom Logic:
Created a HighlightDirective using @HostListener to handle hover effects.
Developed a CreditLabelPipe to transform raw numbers into human-readable strings (e.g., "3 Credits").


Hands-On 04 & 05: The Forms Deep Dive
Template-Driven Forms: Built an Enrollment Request form focusing on simplicity and built-in validators (required, email).
Reactive Forms: Rebuilt the enrollment logic using FormBuilder.
Advanced Validation: Implemented custom synchronous validators (prefix checking) and Async Validators to simulate real-time email availability checks.
Dynamic Controls: Used FormArray to allow students to add/remove multiple courses dynamically in a single submission.


 Key Takeaway
"Moving from Template-driven to Reactive forms highlighted the power of handling form logic in TypeScript. It makes the code much cleaner and significantly easier to unit test."