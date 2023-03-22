# Class 28 notes - Component Lifecycle

## useEffect hook

**What is the main intended use case for the useEffect hook?**
To connect your component to some external system.

**How does the effect’s logic interact with the component?**
mounts a component to the page.

**What is the importance of the return value from the effect’s logic function?**
it returns cleanup code that disconnects from the system in use.
