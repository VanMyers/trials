public class mainOnly {
  public static void main(String[] args) {
    long strt = System.nanoTime();
    int pn = Integer.parseInt(args[0]);
    int tot = 0;
    for(int kj = 0; kj < 1000; kj++){
      if(kj != 0){
        pn = tot;
      }
        int tstr = 2 ;
        int i = 0;
        int[] factors = new int[50];
        for(; tstr*tstr <= pn ;) {
          if (pn%tstr == 0) {
            factors[i] = (tstr);
            pn = pn/tstr;
            i++;
          }
          else {
            tstr++;
          }
        }
        int z = 0;
        factors[i+1] = (pn);
        for(; (factors[z]) != 0; z++) {
          tot +=(factors[z]);
        }
        tot +=(factors[z+1]);
      }
    long fnsh = System.nanoTime();
    long time = fnsh - strt;
    System.out.println("The run time for this trial is " + time + " nanoseconds.");
    }
  }
