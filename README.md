# basic-code
###### public static void reverse() {            //reverse number
                  int k=12356789;
                  int c=0;
               while(k!=0){
                        c=c*10+ k%10;
                         k=k/10;
                    }
              System.out.println(c);
           } 
######  public static void armstrong( ) {                //armstrong number
             int i=0;
             int rem=0,k;
                for(int n=1;n<1000;n++){
                    i=n;
                      rem=0;
                      
                        while (i!=0) {
                                   k=i%10;
                                   rem=rem+k*k*k;
                                   i/=10;
                        }   
                        if(rem==n){
                          System.out.println("Armstrong Number"+rem);
                        }
                } 

           }   
