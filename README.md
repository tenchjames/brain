# Systems

Systems is my take at organizing my notes, thoughts and files in an structured manner. Each system is a collection of notes, thoughts and files that should be easy to remember and understand. My system was inspired by the [Johnny Decimal System](https://johnnydecimal.com/). I have adapted it to add an extra layer of organizations for projects.

## System

A system is a collection of Areas, Categories Topics and Content. A System has a unique identifier which is a two character code followed by three numbers. For example, a special System called the SecondBrain has the identifier 00000 This will provide ample room for the overall collection of systems to grow and allow for multiple projects to be organized in the [Johnny Decimal System](https://johnnydecimal.com/) style.

### System Types

#### Brains

00000 was chosen so it sits at the top of the list of systems. This type of system is a collection of notes, thoughts and files that are not related to a specific project. This system is the root of all other systems. You should start here when it comes to storing data. In general this system reflects personal notes and knowledge. This system is a collection of Areas, Categories and Content.

#### Project

A Project System should be used to organize Jobs and Projects when you will be working on many unique projects and initiatives that are highly focused and need their own organizational strategy. In general you should strive to use your 00000th System unless you work in this specific environment. Remember, you can always reorganize in the future. Beginning with too many Project Systems can lead you down the same path of a chaotic file system. Start with one System. Expand when you really need. It really is as simple as moving some folders around.

Project systems should be begin with a two character code followed by three number. Beginning with AA through ZZ should allow ample room for specific project organization.

---

## Areas

Areas represent very high level groupings. There should be no more than 9 areas in a System. This is based off the ideas in the Johnny Decimal System. The idea is to constrain how many levels you need to look through to drill to the next level. Each Area should be the two character starting point for its range of Category children. The numeric portion should always end in a 0. Label each Area in the format below.

categoryBegin.AreaName

> 10.Education
> 20.People
> 90.Resources

For Project Areas it is recommended to have some standard for your Areas. Using the first N Areas for some standard will make searching and reasoning about where things are located easier.

If you use all 9 of your areas, but your nested Categories and Topics are sparse this may be a sign that your Areas are too narrow and should be broadened. If over a long period of time you fill all of your Areas and your Categories and topics are also all above 80% capacity you may want to consider promoting an Area to its own System.

---

## Categories

Each Area can then be further broken down into up to 9 Categories. A category should be a collection of similar things. Label each Category in the format below.

**You only get 9 of these on purpose**

twoDigitCategoryCodeThatIsNestedInParentArea.CategoryName

> 11.Books
> 12.OnlineCourses
> 21.TeamMembers
> 22.CoWorkers

---

## Topic

A Topic is collection of Content in this related category. **_Topics must be the lowest level of folder nesting_** You should number your topics from 01 to 99. So you get at max 99 topics in a category. If you need to go over this number it is time to rethink your structure and begin to break your Categories down further. Label each Topic in the format below. Topic can also be simple text files. You do not have to nest if it is not needed.

twoDigitTopicCode.Topic

> 01.SallyMyBoss
> 02.SusieMyBossesBoss

---

## Organization

Naming things is important and the default scheme can help you with organizing as well as leaning on programming and scripting to help you index your System. As a general rule avoid spaces in the names of Systems, Areas, Categories and Topics. Be intentional about how and where something is stored using the numerical categories. Overtime you will learn your scheme for traversing directory structures based on your common numbering scheme. The numbering will also help with sorting data in your file system. You can choose the order you want things to be listed by manipulating the positional ordering.

### You forgot some numbers in the scheme

You may have noticed we left off items at the 0th position in each grouping. This is intentional and each of these should be considered special cases that help you organize your Systems. Use these 0th groupings to store meta data about each System, Area, Category and Topic. Below are some recommendations.

In each 0th level it is recommended to add some key helper files. Index.md should be a specific file that contains key links to the nested structures. Revisit this file often to help your system well organized. This file should not container full contents of the child structures. Just links, descriptions and possible tag information.

It is also recommended to include a README.md file that contains an overview of the System and its contents.

Other organizational files can be added to help keep your system organized, searchable and indexable. For example, adding tags to text documents can be a great way to search your collection. However, adding tags without thinking of past usage will get messy really fast. Maintaining a tags file will help you remember if you used the tag #turtle vs #turtles vs #seaturtles already in your collection.

###### System Example

If your 00000 System has exhausted all of its Areas and each of those Areas have Categories and Topics near capacity consider making another 0th System such as 00100.ThirdBrain

**Warning!!!** Just because you can do something, does not mean you should do it. Think hard before you make a ThirdBrain or a FourthBrain. There are very good chances that you can reorganize your SecondBrain.

###### Meta Area Example

Use the 00 Area to hold meta data about the entire System. In fact, the name Meta is a good name for this area. This should hold things that help you administer the system, as well as handling unknowns and generalized topics. This is where you put those Index.md, README.md and other helper files discussed above.

> 00.Meta -> This area will hold meta data about the entire system

Here are some suggested categories that should live inside this Meta Area

> 00.Index -> This Category will hold all those helper files we mentioned above
> 01.Inbox -> Use this to dump stuff you just aren't sure about in the moment. It's better than your desktop. But you must organize it regularly
> 02.Notes -> Use this to dump quick notes that you don't have time to categorize now. Using Zettle time stamps can help keep this organized. Once again clean this often. Create tags, links, categorize and move these to their best place
> 03.Todo -> If you use checklists, or master lists this is a good meta category
> 04.Bookmarks -> Your browser bookmarks are probably a mess. Organize them here.
> 05.Templates -> Make templates you can copy and paste, or use scripting, or even let your note-taking took use to speed up note creation
> 06.Scripts -> Even a few simple automation scripts can help keep your system clean.
> 07.Someday -> Put the things you are thinking about but know you won't get to for a while here. Great for ideas and fleeting thoughts.
> 09.Archive -> As your other categories fill up you may have knowledge that is frequently accessed. Don't delete it, move it to the archive.

###### Category Example

For each Area use the n0th Category to store meta data about your Categories and Topics. Ideally you should store all indexing here to avoid nesting problems.

> Inside yourPeople Area
> 20.People
>
> You will use the 20th Category for Meta data
>
> 20.Meta -> This will hold meta data about the entire Category.

Example Topics in your Category Meta directory

> 00.Index -> Same as above. Files that help you and the system stay organized.
> 06.Scripts -> Specific automation scripts for this category.

Be careful adding much more. Keeping things like Inbox, Notes, Todos at a single top level is probably better. Adding those folders may lead to chaos again. Proceed with caution.

###### Topic Example

For each Category use the n0th Topic to store meta data about the Topics. This is totally optional, and may actually not be desired. However, the space is reserved if you have a need. **Warning!!!** Too much nesting will make searching difficult. Only move data here if necessary. Prefer to keep your indexing at the category level.

Example in the 22.CoWorkers category

> 22.00.Meta

Example folders

> 00.Index -> This may contain a README.md. If necessary an indexing file

## Putting it together

```text
 00000.SecondBrain
       00.Meta
          00.Index
             00.Index.md
             01.README.md
             02.Tags.md
          01.Inbox
             01.DailyChaos
                ramdomexcel.xls
                remindertocleaninbox.md
             02.ProjectRelated
          02.Notes
             2024-01-01T00:00:00.md
             2024-01-01T11:00:00.md
             2024-01-01T12:33:12.md
          03.Todo
             masterlist.md
          04.Bookmarks
          05.Templates
          06.Scripts
          07.Someday
          09.Archive
       10.Education
          10.Meta
             10.Index
          11.CS608
          12.CS630
       20.People
       90.Blog
```
