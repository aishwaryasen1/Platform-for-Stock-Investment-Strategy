# Cloud-Based Platform for Curating Stock Investment Strategy 

In  today’s  fast-paced  ﬁnancial  world,  keeping  up  with  the  latest  market  trends  and 
information  is  crucial  for  successful  trading.  To  address  this  need,  SocialInvest  -  a 
platform  for  stock  investment  strategy,  has  been  developed  to  display  current  and 
historical  trends  of  stocks  for  8  popular  companies,  along  with  the  associated  current 
market  sentiment  from  conventional  and  social  media.
The  platform  leverages  advanced  cloud  computing  technologies  to  process  vast 
amounts  of  unstructured  data  in  real-time,  and  extract  valuable  insights  using 
machine  learning  algorithms.  The  platform  uses  Apache  Beam  in  Cloud  Dataﬂow  to 
create  a  pipeline  that  encapsulates  the  entire  data  transformation  workﬂow.  Various 
PTransforms  are  performed  on  bounded  PCollections  of  incremental  data  from 
Yahoo  Finance  along  with  the  creation  of  sliding  windows  to  compute  15-day  moving 
averages  over  the  stock  information,  in  order  to  obtain  a  more  consolidated  view  of 
the  stock.  The  data  is  preprocessed  and  sentiment  analysis  scores  are  obtained  using 
the  SentimentAnalysisFunction  in  Python.  Further  optimizations  such  as  load 
shedding  and  operator  reordering  will  be  incorporated  as  a  part  of  future  scope  in 
order  to  improve  the  computational  efﬁciency  of  the  pipeline.
Overall,  the  platform  provides  a  powerful  tool  for  investors  to  make  informed 
decisions  based  on  accurate  and  timely  information.  The  dynamic  platform  offers  a 
user-friendly  interface  that  consolidates  various  data  sources  and  provides  tools  to 
analyze  and  interpret  data,  reducing  the  risk  of  ﬁnancial  losses  and  improving 
chances  of  achieving  investment  goals.

