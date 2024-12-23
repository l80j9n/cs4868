java c
Biostat   234 
Final   Data   Analysis   Project   (FDAP) 
January   8,   2024
Abstract Abstract:   Should   be   typed, doublespace,   1 paragraph, maybe   a   table   if   useful,   and   any   equations.      Describe   the   data,   your   tentative   model(s),   source   of   prior information   and   purpose   of   your   analysis.    One   or   a   few   data   plots   can   be   useful.
Please   supply   the   following   information   about   your   project:
●   Project   name.    (< 1 sentence).
●   Purpose   of analysis.    (1   sentence).
●   Outcome   name/definition.
●   Predictor   variable   names/definitions.
●    Sampling   model.
– Some   issues   that   you   may   want   to   explain:    Are   outcomes   correlated?   Is   there   nesting/clustering?   Too   many   predictors?   Missing   data?
– Only   discuss   issues   relevant   to   your   data   set.
●   What   are   the   parameters,   and   what   do   they   mean?    Parameter   names   and descriptions.
●   Prior   information   source.   (principal   investigator, yourself, literature   search)
●   Prior   densities/model.    (For   example:    product   of   independent   normals   for the   regression   coefficients   and   inverse   gamma   for   σ2   ,   etc.)
Type.   A   short   phrase   is   often   sufficient.   Be   brief!
The   purpose   of   this   update   is   to   ensure   that   you   are   on   track   with   your   project.   See   me   if questions   or   issues.
I will get back to   you   if I   see   a   problem/difficulty   or   if   something   is   unclear.
Data You   will   need   to   identify, find   or   assemble   a   data   set   to   analyze   early   in   the   quar-   ter.    Places   to   search   for   data   or   data   sets   are   a)   assembling   or   collecting   your   own   data;   b)   your   current   or   previous   work;   c)   occasionally   your   advisor   may have   a   suggestion;   d) Your   doctoral   thesis   or   master’s   paper   data;   e)   consulting client; f)   CDC or NCHS data   set   (https://www.cdc.gov/nchs/data_access/ ftp_data.htm)   or   census   data.   Getting   a   real   data   set   is   much   preferred.   Real   means   that   someone   cares   about   the   conclusions   of your   analysis.If you get a data set from   the   web   you   will   need   to   do   additional   thinking   to   decide   on   the   purpose   for   your   analysis   and   to   find   a   source   of   prior   information.   You   may   not   take   a   data   set   from   the   notes, from   a   previous   statistics   course   like   200A   or   from   Hoff’s,   Gelman’s   or   Congdon’s   books,   nor   from   the   UCI   machine learning   repository,   nor   Kaggle.
The Final Report 
Your   report   must:
●   be   at   most   4   typed   double   spaced   pages,
●   be   appropriately   supplemented   with   graphs   and   tables   as   needed   in   the   appendix.   The   appendix   is   not   part   of the   4   page   limit.
●   include   a   sensitivity   analysis   of   the   main   results   to   key   assumptions.
●   include   proper   informative   priors   for   at   least   some   parameters.    The   jus-   tification   for   your   prior   parameters   will   form   the   basis   for   part   of   the grade.
●   report   plot(s)   of   the   posteriors   of   interest.
●   include   your   JAGS   code   in   the   appendix   –   helps   me   debug   sometimes.
●    interpret the numerical results in terms of   the underlying problem.    This   is   vital   for   any   data   analysis.
●   label   appropriately   all   tables   and   graphs
●   refer   to   all   tables   and   graphs   in   the   main   text.
The   outline   of your   paper   might   include   many   of the   following   sections:
1.      Problem   motivation      goal(s)   of   the   analysis.
2.      Description   of   the   data   set.
3.      Description   of   prior   information. What   it   is   and   how   you   translate   that   to   a   pr代 写Biostat 234 Final Data Analysis Project 2024
代做程序编程语言ior   density.
4.    Choice   of   model(s)   and   prior(s).
5.      Mathematical specification of   the model, that is, using   “twiddle notation”,
for   example   yi      ~ N(µi   ,σi(2)).
6.      Numerical   and   graphical   results.
7.    Convergence   issues.
8.    Problems   encountered.
9.    Sensitivity   Analysis.
10.    Conclusion/discussion.
11.    References.
12.    Appendix:   R   and   JAGS   Code,   Necessary   Figures   and   Tables.   A   regression-type   model   or   hierarchical   model   is   recommended.Grading The   project   will   be   graded   on   the   writing,   including   English,   orga-   nization,   neatness   and   flow;   and   content,   including justification   and   sensibility   of   the   analysis.    Allowance   will   be    made   for   the   complexity   of   the   problem.   Simple data sets will need   to   have   substantially   more   thorough   sensitivity   anal-   yses   as   compared with   complicated   data   sets   and   models where   getting   a   single   posterior   requires   a   substantial   amount   of work.Feedback Please see me if you aren’t   sure   whether   a   particular   analysis/data   set/problem   is   appropriate   or   doable.   We’ll   talk   through   your   goals   and   interests and   the   data   set.
Turn it in Please   turn   in   a   PDF   to   Bruin   Learn   for   the   abstracts   and   the   final   project.
Each   person   must   analyze   a   different   data   set.   Joint   custody   of   data   is   not allowed.
More on Data Sources 
Some   suggestions   on   data   sources:
●   Collecting   your   own   data.
●   Your   research   group.
●   NCHS/CDC https://www   .cdc.gov/nchs/data_access/ftp_data.htm.
●    Census   data.
●    Google’s dataset search engine: https://datasetsearch.research.google .   com   (I   haven’t   checked   this   out.)
●   Data.gov: https://www.data.gov 
● https://data.mendeley.com (I   haven’t   checked this out.)
●   Our world in data https://ourworldindata.org/ 
●   Michigan   ICPSR https://www.icpsr.umich.edu/web/pages/ They   try   to   be   careful   about   collecting   sufficient   information.For   any   data   set,   particularly   from   the   larger   sources,   the   data   may   be   lacking   in   documentation,   and   that   will   make   it   hard   to   use.   So   please   check   that   it   is   usable!   For most any of these sources,   you   need to   provide   a   “reason   for   being”:   What   is   the   purpose   of your   data   analysis?For   some   data   sources   you   have   to   decide   on   the   variables   you   want   to   use   –   the   data   source   is   a   huge   collection   of   variables   for    (say)   countries,   states,   counties,   cities.   For   another   example,   Wikipedia   provides   lots   of   data   sets   (one variable   at   a   time!)   for   many   or   all   countries.Some   places   are   not   good   sources   for   data   because   they   may   have   (a)   poor   curation –   variables   are   not   clearly   defined,   zeros   or   missing   data   are   not   identified,    (b)   the   “story”   isn’t   described,      the   reason   the   data   was   collected   in   the   first   place   is   not   given.      Example   of poor   sources   include   Kaggle   and   UCI   machine   learning   repository   and most textbook datasets.   The large repositories   (or link repositories) are scrapping   data   and   probably   are   not   checking   on   data   and   story/curation   quality.You   also   can’t   take   a   data   set   from   one   of your   classes   or   the   corresponding   text-   book,   or   from   the   Gelman   et   al   BDA   book.   Sports   data   sets,   while   major   league   fun,   can   be   difficult   to   work   with:    make   sure   the   predictors   you   were   thinking   of   aren’t   actually   a   part   of   your   outcome   and   that   observations   are   independent      (hint:    they   usually   aren’t!).


         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
