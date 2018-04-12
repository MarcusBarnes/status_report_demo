# Status Report Demo
A demonstration of using hook_requirements() against a checklist in the module configuration.  The use-case for this demo is when a module requires system configuration outside of the module.  By using hook_requirements during the runtime phase, we can provide additional reminders to site administrators to carry out task in a checklist of modules installation steps that may require configuration beyond what is normally possible with module requirement and update functionality.
