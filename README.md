# 
#include<stdio.h>
#include<stdlib.h>
#define TOT_FRAMES7 enum{NO,YES}ACK;
int main()
{
	int wait_time,i=1;ACK=YES;
	for(i=1;i<=TOT_FRAMES;)
	{
		if(ACK==YES&&i=1)
		{
			printf("\n SENDER:ACK for frame%d recieved.\n",i-1);
			}
		    printf("\nSENDER:frame%d sent,waiting for ACK...\n",i);ACK=no;
		    wait_time=rand()%4+1;
		    if(wait_time==TIMEOUT)
		    {
		    	printf("SENDER:ACK not received for frame %d=>TIMEOUT Resending Frame---",i);
		    }
		    else
		    {
		    	sleep(RTT);
		    	printf("\n RECEIVER:frame%d received,ACK sent\n",i);
		    	printf("---");
		    	ACK=YES;
		    	i++;
		    }
	}
	return0;
}
			}
			}
			}
	}
}
