# HashtagSyn
HashtagSyn is a tool design for find the top related hashtags to a hashtag.

HashtagSyn improves the readability and the relevancy of hashtags found compared to a simple research.

For instance:

| Hashtags | Baseline context | HashtagSyn context |
| --- | --- | --- |
| #maternalhealth | #MaternalHealth #SincerelyVee #SWOP2017pic #Malawi #equality #TeamVee #globalhealth #GBV #LamazeAdvocacy17 #Nkhatabay | #MaternalHealth #globalhealth #women #pregnancy |
| #ps4 | #PS4 #BO3 #XB1 #xbox #gaming #twitch #PSN #Destiny2 #XboxOne #PS4sharepic | #PS4 #xbox #XboxOne #gaming #twitch #Gaming |

The science behind HashtagSyn is described in:

      @article{henry2018filter,
      title={Filter hashtag context through an original data cleaning method},
      author={Henry, Didier and Stattner, Erick and Collard, Martine},
      journal={Procedia Computer Science},
      volume={130},
      pages={464--471},
      year={2018},
      publisher={Elsevier}
      }

If you find this tool useful in your research, please consider to cite us.

---------------------------------------------------------------------------
How it works?

java -jar HashtagSyn.jar [#hashtag]

        Example: java -jar HashtagSyn.jar "#ps4"

---------------------------------------------------------------------------
Developped by Didier Henry PhD student in computer science at the University of French West Indies (Guadeloupe)
