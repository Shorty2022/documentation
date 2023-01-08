# Persönliche Dokumentation

### React Key Terms
React Components sind Bausteine einer React-Anwendung, die eine einzelne Funktionalität oder ein bestimmtes Verhalten implementieren und sich in andere Components integrieren lassen können. Sie bestehen aus HTML-ähnlichem JSX-Code und haben oft einen eigenen Zustand und eigene Methoden, die sie verwalten. Änderungen im Zustand oder in den Eigenschaften eines Components können dazu führen, dass dieses neu gerendert wird und die Änderungen in der Benutzeroberfläche angezeigt wird.

###  States https://beta.reactjs.org/learn/managing-state
Der State in React ist ein Objekt, das bestimmte Eigenschaften eines Components beschreibt und sich im Laufe der Zeit ändern kann. Der Zustand wird innerhalb des Components verwaltet und kann über Props an untergeordnete Components übergeben werden. Ein State speichert dynamische Daten und kann Neurendering auslösen. States sollen so gekapselt und spezifisch wie möglich sein.

### Zustand https://github.com/pmndrs/zustand
 Zustand ist eine kleine, schnelle und skalierbare State-Management-Solution. Es besittz eine bequeme APi basierend auf Hooks, hat wenig boilerplate und ist nicht wie Redux rechthaberisch.

### Context https://beta.reactjs.org/reference/react/useContext
Der Context ermöglicht, Daten und Funktionalitäten, die sich auf mehrere Components in der Komponentenstruktur auswirken, zentral zu verwalten. Daten können an untergeordnete Components weitergeleitet werden zb.: aktueller Benutzer, Sprachpaket oder Farbschema.

### Hooks https://beta.reactjs.org/reference/react
React Hooks sind eine Art von Funktionen in der React-Bibliothek, die es ermöglichen, den Zustand und andere Funktionalitäten von Components zu verwenden, ohne eine Klasse zu verwenden.

- useState: ermöglicht, den Zustand eines Components zu verwalten.
- useEffect: ermöglicht, Seiteneffekte in Function Components auszulösen.
- useContext: Zugriff auf den bereitgestellten React Context.
- useRef: ermöglicht, eine Referenz auf ein DOM-Element / JavaScript-Objekt
- useReducer: ähnlich wie useState, aber er ermöglicht es, den Zustand mit reduzierten Funktionen zu verwalten, die als Dispatcher fungieren.

### Router https://reactrouter.com/en/main
Der React Router ermöglicht, die Navigation zu verwalten und die Benutzeroberfläche basierend auf der aktuellen URL des Browsers zu rendern. Der React Router definiert Routen für verschiedene Teile der Anwendung und verwendet dann Components, um die Benutzeroberfläche basierend auf der aktuellen Route zu rendern.

### Internationalisation (i18n) https://next-intl-docs.vercel.app/
Internationalisierung (i18n) in React ist der Prozess der Anpassung der Benutzeroberfläche einer Anwendung an die sprachlichen und kulturellen Anforderungen von Benutzern in verschiedenen Ländern oder Regionen. Eine gute Library dafür sind use-intl oder next-intl.

### Accessibility https://www.radix-ui.com/
Components und Anwendungen sollen so gestaltet werden, dass sie für alle Benutzer zugänglich und nutzbar sind. Dies schließt Benutzern ein, die assistive Technologien wie Screenreader oder andere Hilfsmittel verwenden. Eine gute Library dafür ist RadixUI.

### Data Fetching https://swr.vercel.app/
<![endif]--> Data Fetching bezieht sich auf den Prozess, Daten von externen APIs oder anderen Quellen in einer React-Anwendung abzurufen und zu verwenden. Data Fetching ist wichtig, um dynamische Daten in einer Anwendung anzeigen zu können. Beim Datafetching sollen Status wie Loading oder Fehlermeldung implementiert werden. Eine gute Library dafür ist SWR.

### Next.JS
Next.js ist ein Framework für Server-seitiges Rendering von React-Anwendungen. Es wurde entwickelt, um es Entwicklern zu erleichtern, schnell und einfach leistungsstarke Anwendungen mit Server-seitigem Rendering und automatischer Code-Splitting zu erstellen. Wichtigste Features sind: Routing, Data Fetching, Tooling sowie Server/Static/InitalProps.

### Testing https://jestjs.io/docs/tutorial-react/ und https://docs.cypress.io/
Testing in React ist Key to Success. Gute Frameworks für Testing sind Jest und Cypress.
