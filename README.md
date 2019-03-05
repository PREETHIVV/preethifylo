# preethifylo
import java.util.*; 
import java.util.Timer;
import java.util.Date;
import java.util.TimerTask;

  
public class housekeeping { 
    public static void main(String args[]) 
    { 
  
        // Creating an empty asset 
        assetid<String> assetid 
            = new Stack<String>(); 
  
        // Use add() method 
        // to add elements in the Stack 
        assetid.add("table"); 
        assetid.add("chair"); 
        assetid.add("carpet"); 
        assetid.add("soapdispenser"); 
        assetid.add("coffeemachine"); 
        assetid.add("netwoking");
assetid.add("wiring");
assetid.add("generator");
assetid.add("electricals");
assetid.add("firstfloor");
assetid.add("restroom");
assetid.add("meetingroomone");
assetid.add("meetingroomtwo");
assetid.add("meetingroomthree");



Timer timeofallocation;

    public Reminder(int seconds) {
        timeofallocation = new Timeofallocation();
        timeofallocation.schedule(new RemindTask(), seconds*1000);
	}



public class timeofallocation extends Taskstobeperformedby {

    @Override
    public void run() {
        System.out.println("Timer task started at:"+new Date());
        completeTask();
        System.out.println("Timer task finished at:"+new Date());
    }

    private void completeTask() {
        try {
            //assuming it takes 20 secs to complete the task
            Thread.sleep(20000);
        } catch (InterruptedException e) {
            e.printStackTrace();
        }
    }






public static void main(String args[]) {




public String gettable () {
        return table;
    }
public String getchair() {
        return chair ;
    }
public String getcarpet () {
        return carpet ;
    }
public String getsoapdispenser() {
        return soap dispenser;
    }
public String getcoffeemachine() {
        return coffeemachine;
    }
public String getnetwoking() {
        return netwoking;
    }
public String getwiring() {
        return wiring;
    }
public String getgenerator() {
        return generator;
    }
public String getelectricals() {
        return electricals;
    }
public String getfirstfloor() {
        return firstfloor;
    }
public String getrestroom() {
        return restroom;
    }
public String getmeetingroomone() {
        return meetingroomone;
    }
public String getmeetingroomtwo() {
        return meetingroomtwo;
    }
public String getmeetingroomthree() {
        return meetingroomthree;
    }

        


    class RemindTask extends TimerTask {
        public void run() {
            System.out.println("Time's up!");
            timer.cancel(); //Terminate the timer thread
        }
    }

    
        
    



housekeeping vacuumingthefloor = housekeeping.getInstance();
housekeeping.set(vacuumingthefloor.HOUR_OF_DAY, 5);
housekeeping.set(vacuumingthefloor.MINUTE, 1);
housekeeping.set(vacuumingthefloor.SECOND, 0);
housekeeping.set(vacuumingthefloor.WEEK, 7);
housekeeping.set(vacuumingthefloor.YEAR, 365);


housekeeping moppingthefloor = housekeeping.getInstance();
housekeeping.set(moppingthefloor.HOUR_OF_DAY, 5);
housekeeping.set(moppingthefloor.MINUTE, 1);
housekeeping.set(moppingthefloor.SECOND, 0);
housekeeping.set(moppingthefloor.WEEK, 7);
housekeeping.set(moppingthefloor.YEAR, 365);


housekeeping refillingthesoapdispenser = housekeeping.getInstance();
housekeeping.set(refillingthesoapdispenser.HOUR_OF_DAY, 5);
housekeeping.set(refillingthesoapdispenser.MINUTE, 1);
housekeeping.set(refillingthesoapdispenser.SECOND, 0);
housekeeping.set(refillingthesoapdispenser.WEEK, 7);
housekeeping.set(refillingthesoapdispenser.YEAR, 365);


housekeeping makingcoffee = housekeeping.getInstance();
housekeeping.set(makingcoffee.HOUR_OF_DAY, 5);
housekeeping.set(makingcoffee.MINUTE, 1);
housekeeping.set(makingcoffee.SECOND, 0);
housekeeping.set(makingcoffee.WEEK, 7);
housekeeping.set(makingcoffee.YEAR, 365);





Date time = housekeeping.getTime();

timeofallocation = new Timeofallocation();
timeofallocation.schedule(new RemindTask(), time);



public EmployeeResource() {
    }
    @GET   // this method process GET request from worker
    @Produces("application/json")   // sends JSON
    public String getJson( @PathParam("workerid") int empno) {     
      switch(workerid) {
          case 1 :
              return "{'name':'George Koch', 'age':58}";
          case 2:
              return "{'name':'Peter Norton', 'age':50}";
          default:
              return "{'name':'unknown', 'age':-1}";
      } // end of switch
   } // end of getJson()




public String getvacuumingthefloor() {
        return vacuumingthefloor;
    }

public String moppingthefloor () {
        return moppingthefloor;
    }
public String () {
        return wiring;
    }
public int getwiring() {
        return wiring;
    }
public int getwiring() {
        return wiring;
    }
public int getwiring() {
        return wiring;
    }
public int getwiring() {
        return wiring;
    }
public int getwiring() {
        return wiring;
    }

    






    
    
new Reminder(5);
        System.out.println("Task scheduled.");


{
        TimerTask timerTask = new MyTimerTask();
        //running timer task as daemon thread
        Timer timer = new Timer(true);
        timer.scheduleAtFixedRate(timerTask, 0, 10*1000);
        System.out.println("TimerTask started");
        //cancel after sometime
        try {
            Thread.sleep(120000);
        } catch (InterruptedException e) {
            e.printStackTrace();
        }
        timer.cancel();
        System.out.println("TimerTask cancelled");
        try {
            Thread.sleep(30000);
        } catch (InterruptedException e) {
            e.printStackTrace();
        }









    }












}



