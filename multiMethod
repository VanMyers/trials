public class multiMethod {
  public static int priFac(int kj, int tot) {
    int tstr = 2 ;
    int i = 0;
    int[] factors = new int[50];
    int pn = tot;
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
    factors[i+1] = pn;
    for(; (factors[z]) != 0; z++) {
      tot +=(factors[z]);
    }
    tot +=(factors[z+1]);
    return(tot);
  }
  public static void calculateTime(long startTime){
    long endTime = System.nanoTime();
    long runTime = endTime - startTime;
    System.out.println("The runtime for this trial is " + runTime + " nanoseconds");
  }
  public static void main(String[] args) {
    long start = System.nanoTime();
    int total = Integer.parseInt(args[0]);
    for(int i =0; i < 1000; i++) {
      total = priFac(i, total);
    }
    calculateTime(start);
  }
}
