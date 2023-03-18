# Java-Swing-JNotpad

For text editing use JTextArea component. For each open document a new instance of JTextArea is create for it; this component will be then (indirectly) added to the JTabbedPane. I say indirectly because it is wrap into JScrollPane with JScrollPane into JPanel which will eventually be added into the JTabbedPane.

### Application provides the following functionality to the user: 
* creating a new blank document
+ opening existing document
+ saving document
+ saving-as document (warn user if file already exists)
+ close document shown it a tab (and remove that tab) 
+ cut/copy/paste text, • statistical info
+ exiting application. 

### All of those actions must be available from: 
+ menus (organize them as you see fit)
+ dockable toolbar
+ keyboard shortcuts.
