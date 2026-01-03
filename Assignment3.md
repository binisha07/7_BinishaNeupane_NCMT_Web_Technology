# Web Technology
## Assignment III

## Student Name: Binisha Neupane                    Date: 2026-01-02
## Roll no.: 07                                     Program: BIT(A)

# Chapter 2: Website Structure Design
## Group A: Short Questions
### 1. Define Information Architecture(IA).
### => Information Architecture is the practice of structuring, organizing, and labeling content in digital spaces to make information findable, understandable, and usable for people.

### 2. What is a "Wireframe"?
### => A wireframe is a basic, skeletal blueprint of a website, app, or digital product, showing layout, content structure, and functionality without detailed visuals like colors or images, focusing purely on where elements (buttons, text areas, images) go and how users navigate

### 3. Explain the concept of 'Cognitive Friction" in web design.
### => Cognitive friction in web design is the unnecessary mental effort users exert when an interface doesn't align with their expectations, forcing them to stop, think, or learn new ways to complete tasks, leading to frustration and abandonment.

### 4. Why should URL slugs use hyphens instead of underscores?
### => URL slugs should use hyphens (-) instead of underscores (_) because search engines like Google interpret hyphens as word separators, improving readability and understanding for both bots and users, while underscores can be seen as part of a single, unreadable word

## Group B: Long Questions
### 5. Compare and contrast Hierarchical (Tree) structure and Linear (Sequential) structure. Give an example of when to use each.
### => Hierarchical (Tree) structures organize data in levels with parent-child relationships, allowing complex branching, while Linear (Sequential) structures arrange data in a single, ordered line with one successor, making them simple and fast for straightforward tasks. In hierarchical structure data are organized in levels, from a root node down to leaves, showing parent-child relationships with branching paths but in linear structure data elements are arranged in a single, continuous sequence, where each element has a direct predecessor and successor.Tree structure is non-linear, multi-level, has complex relationships, uses scattered memory and is harder to implement. While linear structure is Single-level, sequential traversal, simpler to implement and often uses contiguous memory.Examples of tree structure are file system, Company Organization Charts,decision trees etc. and the examples of linear structure are arrays and linked lists Stacks queues etc.

### 6. Explain the ”Three-Click Rule” and its significance in User Experience (UX) design.
### => The three-click rule is an informal principle in UX design that suggests that users should be able to find the information or complete a task on a website within three clicks or fewer. The rule emphasizes the importance of keeping navigation paths short and intuitive to enhance the user experience and prevent frustration.By minimizing the number of clicks required to find information, the three-click rule improves user efficiency. Users can quickly access the content they need or achieve their goals without unnecessary navigation steps, saving time and effort.The three-click rule encourages designers to optimize the navigation structure and information architecture. This results in a more organized and intuitive interface where content and functionality are logically grouped and easily accessible.  A simplified experience allows users to stay focused, making the overall interaction more enjoyable.

### 7. ”Plan before you do.” Explain how tools like Card Sorting and Flowcharts help in planning a website’s structure.
### => Tools like card sorting and flowcharts are crucial "plan before you do" methods that help define a website's structure by organizing information and visualizing user paths before development begins. Card sorting is a user-centered design technique where participants group a website's topics into categories that make sense to them.  This process helps determine intuitive categorization and labeling of content, ensuring that the site's structure aligns with users' mental models. By revealing how users expect information to be grouped, card sorting directly informs the design of the main navigation and menu structures, making the site easier to browse. Flowcharts are visual diagrams that map out the sequence of steps a user takes to complete a task, or illustrate the hierarchy of pages on a website. They provide a top-down view of the entire website, showing how different sections and pages connect, which helps identify potential dead ends or overly complex paths.By charting user flows for key tasks (e.g., purchasing a product, signing up for a newsletter), designers can optimize the path, removing unnecessary steps and reducing friction.

## Group C: Scenario-Based Questions
### 8. You are designing a website for a University. It has hundreds of pages (Admissions,Departments, Alumni, News). Which structural model would you choose? Draw a rough diagram and justify your choice.
### => For a university, a hierarchical or tree structure is a suitable model because it allows for a clear organization of a large number of pages by topic and subtopic. This structure starts with a main homepage and branches out into major sections like admissions, departments, alumni, and news. Each of these sections can then have its own sub-pages, creating a logical flow that is easy for users to navigate. It helps users find specific information efficiently by following a logical path from general to specific information.A rough diagram might look like this:
### Homepage (University Website)
### ->Admissions
### ->Undergraduate
### ->Graduate
### ->Financial Aid
### Departments
### ->Arts & Sciences
### ->Engineering
### ->Business
### Alumni
### ->Events
### ->Donations
### ->Newsletters
### News
### ->Current Events
### ->Archives

### 9. A user visits a website but leaves within 10 seconds because they cannot find the navigation menu, which is hidden behind a small icon on a desktop screen. Analyze this design failure using the ”KISS” (Keep It Simple) principle.
### => The design failure violates the "KISS" principle by making the navigation menu non-obvious and difficult to find, thus failing to keep the user interface simple and intuitive. The "Keep It Simple, Stupid" (KISS) principle in design emphasizes simplicity and clear communication. Hiding a primary navigation menu behind a small, non-standard icon on a desktop interface adds unnecessary complexity for the user may be a design failure. Users expect common elements like navigation to be easily discoverable and follow established conventions (e.g., standard menu bars or clearly labeled links). The design forces the user to think and search for the menu, which increases cognitive load and friction, leading to a poor user experience and abandonment.A simpler design would make the navigation immediately visible and accessible, adhering to the principle that things work best when they are simple.

### 10. An e-commerce website has a URL structure like www.shop.com/prod?id=55&cat=9. Explain why this is bad for both users and Search Engines (SEO), and propose a better structure using Page Slugs.
### => The current URL structure (www.shop.com/prod?id=55&cat=9) is bad for the following reasons:
### Poor User Experience (UX): The URL is not human-readable, making it difficult for users to understand the page's content, remember the link, or share it with others. 
### Bad for Search Engines (SEO): Search engines prefer descriptive URLs that help them understand the page's content. Parameter-heavy URLs are less likely to be clicked on in search results and can lead to duplicate content issues, where search engines might treat different URLs as separate pages even if they display the same content. 
### Lack of Keywords: The current structure uses generic IDs and categories, missing an opportunity to include relevant keywords that could boost search visibility. 
### A better structure using page slugs would be: www.shop.com/products/category-name/product-name-sku
### For example: www.shop.com/electronics/cameras/canon-eos-r5-mirrorless-camera
### This proposed structure is beneficial because:
### It is descriptive: Both users and search engines can immediately tell what the page is about. 
### It includes keywords: The product name and category are included, which helps with SEO rankings. 
### It provides a logical hierarchy: The structure follows the website's organization, which improves site navigation and helps search engines crawl the site more efficiently.




