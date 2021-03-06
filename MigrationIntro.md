### What is Cloud Migration?
Ans:- Cloud migration is the process of moving data, applications or other business elements from an organization's onsite computers to the cloud, moving them from one cloud environment to another.

### Why migration is important?
Ans:-  Migration is important in many aspects like a Business owner wants to expand his business, or has some future plan. Or he is thinking about to improve profit by expanding the business or he is expanding the business world wide. There are some important point to think here:
    1. Scale application according to the application traffic.
    2. Reduce operational cost.
    3. faster application implementation.
    4. Business can have global reach.
    5. Better disaster recovery strategy.

### Phases of Migration:
#### 1. Opportunity Evaluation: 
    First we need to evaluate the opportunity like does we need a migration or can we   afford this migration on the basis of our existing infrastructure. Then perform all of the research and take the suitable actions and take a call on it.

#### 2. Portfolio Discovery and planning: In this situation, we analysis our arcitecture completely.
    Like we have various databases ,we monitor all the capacity and infrastructure on premises and all, so we know these are the existing system that we are use, if i do migrate to cloud these the system or architecture that are available, so when i do migrate would it be benificial and or convinent and if i migrate then how i can do that it basically means planning.

    The complexity will also influence how you migrate. Because it’s easy to lift-and-shift a modern application hosted on a virtualized environment, and there’s typically less technical debt associated with something developed 3 years ago versus 20 years ago, we find a strong bias toward rehosting (aka “lift-and-shift”). And, because it’s simply not possible to lift-and-shift a mainframe, we also find a strong bias toward feature rationalization and re-architecting.

    This is when they determine what’s in their environment, what are the interdependencies, what’s going to be easy to migrate and what’s going to be hard to migrate, and how they’ll migrate each application.

#### 3. 	a). Application Design  b). Migrating and validating applications 

    	How can we desgin, there are some factor that we need to considered when we actually design migration strategy. On the basis of these factor we generally go and design the startegies and on the basis of these we migrate and then we validate our application as we need or not.

    	The focus of the migration moves from the portfolio level to the individual application level, and each application is designed, migrated, and validated according to one of the 6 application migration strategies known as 6 R's.

    	Start with the least complex application, learn how to migrate while learning more about the target platform, and build toward the more complex application migrations as your organization becomes more cloud and migration fluent.
 

#### 4. Modern Operating Model: 
    	Finally, as applications are migrated, you iterate on your new foundation, turn off old systems, and constantly iterate toward a modern operating model.
    	Once we migrate to cloud we need to take care of various things.
    	-> did we need to stick to the architecture that we have
    	-> can we upgrade to something that we can do.
    	Basically performing optimizations and all on the cliud infrastructure.


### Migration Strategies for AWS.

#### Formulating a Migration Strategy:
	This is when they determine what’s in the environment, what are the interdependencies, what’s going to be easy to migrate and what’s going to be hard to migrate, and how we’ll migrate each application.

	Using this knowledge, organizations can outline a plan (which should be considered subject to change as they progress through their migration and learn) on how they’ll approach migrating each of the applications in their portfolio and in what order.

	The complexity of migrating existing applications varies, depending on the architecture and existing licensing arrangements. If I think about the universe of applications to migrate on a spectrum of complexity, I’d put a virtualized, service-oriented architecture on the low-complexity end of the spectrum, and a monolithic mainframe at the high-complexity end of the spectrum.

### 6 R's strategy

#### 1. Re-hosting (Otherwise known as “lift-and-shift.”) :- 
    When we are talking about re-hosting basically we move out application 		from one host to the other or basically to cloud that means we simply migrating our application even if we don't go ahead 	   restructure or rescale our application .
	
	Most rehosting can be automated with tools (e.g. CloudEndure Migration, AWS VM Import/Export), although some customers prefer to do this manually as they learn how to apply their legacy systems to the new cloud platform.

	It is also found that applications are easier to optimize/re-architect once they’re already running in the cloud. Partly because your organization will have developed better skills to do so, and partly because the hard part — migrating the application, data, and traffic — has already been done.

#### 2. Replatforming (I sometimes call this “lift-tinker-and-shift.) :- 
    It is quite similar to the re-hosting but the difference is you tinker means you perform some small changes in the application.

    In this we basically lift our application, make some changes and then shift it over the cloud.

    Here you might make a few cloud (or other) optimizations in order to achieve some tangible benefit, but you aren’t otherwise changing the core architecture of the application.

    A large media company we work with migrated hundreds of web servers it ran on-premises to AWS, and, in the process, it moved from WebLogic (a Java application container that requires an expensive license) to Apache Tomcat, an open-source equivalent. This media company saved millions in licensing costs on top of the savings and agility it gained by migrating to AWS.

#### 3. Repurchasing :-Repurchasing as a move to a SaaS platform. Moving a CRM to Salesforce.com.

    CRM:- CRM stands for “customer relationship management” and it’s software that stores customer contact information like names, addresses, and phone numbers, as well as keeps track of customer activity like website visits, phone calls, email, and more.

#### 4. Refactoring / Re-architecting — 
    Re-imagining how the application is architected and developed, typically using cloud-native features.

    In this starategy we basically add features, scale , or performance on the cloud that would otherwise be difficult to achieve in the application's existing environment.

    In this approach we are basically looking into the migration of monolithic architecture to a service-oriented (or sever-less) architecture to boast agility or improve business continuity. This strategy tends to be most expensive.

#### 5. Retire (Get rid of)— 
    Once we are discovered everything in our environment, we might have something or certain services, which is not beneficial or no longer useful, and simply be turned off. These savings can boost the business case. 

#### 6. Retaining-- 
    Retaining the application means we are moving out application from an on-premise env to the cloud env. In this there are some situation where we might want to run some part of the application on premise and certain part of the application on the cloud so we can take the call on which application to retain on premise env and which part to cloud.