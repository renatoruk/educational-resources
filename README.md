# Educational resources

This is my place for storing all the videos, lessons, books and everything in between that contributes to the knowledge of software development and related skills.

Each new entry should be given a checkbox and after its completion I should write a few key takeaways for a later reference.

### React
- [ ] [Practical Redux - Mark Erikson](https://blog.isquaredsoftware.com/2016/10/practical-redux-part-0-introduction/)
- [x] [Profiling React Performance](https://addyosmani.com/blog/profiling-react-js/)
    - programmatic profiling of React apps with React Profiler API
- [ ] [How Next.js and Gatsby work and their differences](https://www.youtube.com/watch?v=xC4Yq_mXvPM&ab_channel=Prismic)

### JS
- [ ] https://www.youtube.com/watch?time_continue=2&v=8aGhZQkoFbQ&feature=emb_logo&ab_channel=JSConf

### Functional programming
- [ ] [Why Isn't Functional Programming the Norm? – Richard Feldman](https://www.youtube.com/watch?v=QyJZzq0v7Z4)

### Creative Front-end
- [x] [Behind the scenes of We Cargo](https://medium.com/epicagency/behind-the-scenes-of-we-cargo-3999f5f559c)
  - WebGL and DOM can be combined by an abstraction layer
  - WebGL can sometimes be implemented as progressive enhancement, rendered underneath the dom elements

### Time management
- [x] [Why We're Bad at Estimating Time](https://zapier.com/blog/how-to-estimate-time/) 
  - we often underestimate how long will a task take and there is phsychological reasoning behind that (optimism bias)
  - overcoming the planning fallacy: 
    - Use Historical Data (time tracking)
    - Have Someone Else Estimate for You (we estimate more realistically for others)
    - Estimate in Ranges, or Build in Time for Delays ([cone of uncertanty](https://user-images.githubusercontent.com/12981417/68505059-af593400-0266-11ea-8997-703625a60b66.png))
    - Use Three-Point Estimations
    - Calculate Your Fudge Ratio (the percentage by which you always underestimate)
    - Estimate During the Low Point of Your Day (pessimistic approach, usually after lunch)
    
### Web app performance
- [x] https://3perf.com/blog/notion/ - analysing Notion app's speed
    - key takeaways for improving app loading performance:
        - code splitting (lower parsing and execution time)
        - polyfilling only for browsers that need it
        - removing unneccessary dependencies
        
        
### Testing
- [ ] https://medium.com/swlh/publish-your-cypress-test-report-with-github-actions-47248788713a
    
### Architecture and design
- [ ] [Designing Even Larger Applications - Malte Ubl](https://medium.com/@cramforce/designing-even-larger-applications-460ee029012d) 

### Development practices
- [x] [GOTO 2016 • Software, Faster • Dan North](https://www.youtube.com/watch?v=USc-yLHXNUg&feature=youtu.be&t=1053&ab_channel=GOTOConferences)
    - less code is often better than more code (seems super obvious)
    - patterns of software team behaviour:
        - **spike and stabilize**
            - half of codebase should be short
            - technique of deliberately deciding if the code is young or old
            - spike 
              — experiment until you have the goal done
              - have time constraint
              - do not deliberately decide if the code is quality upfront
              - learning is the main goal
            - stabilize
              - going back to the "experiment" and cleaning up
              - writing tests, refactoring
              - criteria for stabilization:
                  - going back to it second time
                  - going back to it in 6 weeks
            - we end up with code that's new and spikey or old and stable
        - **hair trigger**
          - if a team can not deploy its own code, it can never go fast
          - responsibility and carefullness
          - move fast and be careful, deploy and learn (but have rollback ideally, a safety net)
        - **shallow silos**
          - in agile methodology anyone should be able to work on everything
          - having constraints in team makes the team effective, not everyone needs to do everything, but a team should collaborate and get together to sync
        - **ginger cake**
          - pattern for getting started quickly with something
          - by having great knowledge on a part of the code, copying is fine because you already know about the ins and outs
        - **burning ships**
            - learning pattern
            - experimental strategy of commiting to a goal and forcing yourself to only solve problems and goals without additional learning
            - knowning "just enough" for getting stuff done
            - constraints:
                - deadline
                - running out of other options
                - information
            - example: building a todo app in C#, but not knowing the language
                - not watching tutorials or reading books
                - learning by doing and experimenting
                - learning only enough for the next goal
                

### Project Management
- [x] [Product Management Mental Models for Everyone](https://blackboxofpm.com/product-management-mental-models-for-everyone-31e7828cb50b?gi=617d96bb2cb9) 
    - Mental models are simple expressions of complex processes or relationships. These models are accumulated over time by an individual and used to make faster and better decisions.
    - there are many mental models in the product development (e.g. pareto principle), but sticking only to one will probably give you incorrect image about the world or scenario
    - feature/product certanty should define *how many resources* should you invest into building something new
        - e.g. for an experimental product it's better to start small and fast and learn from the customer
        
### Critical Thinking
- [x] https://untools.co/
    - Collection of thinking tools and frameworks to help you solve problems, make decisions and understand systems.

### Dicovery & specification
- [ ] [User Story Mapping with Jeff Patton](https://www.youtube.com/watch?time_continue=225&v=AorAgSrHjKM&feature=emb_title&ab_channel=ComsystoReplyGmbH)
- [ ] https://medium.com/tribalscale/writing-technical-user-stories-434bf96f1dd5


### Technical leadership
* [x] https://medium.com/coleadership/what-does-it-take-to-be-a-successful-tech-lead-d133ee18677
    - A good tech lead excels in delivery and execution
    - A good tech lead builds a thriving team
    - A good tech lead builds alignment
    - A good tech lead balances priorities
    - A good tech lead is clear about what they want
