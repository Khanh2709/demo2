README.md
package demo;


    	public interface Vehicle {

    	   void go();
    	}
      public class BIke implements Vehicle {

	@Override
	public void go() {
		System.out.println("Move by Bike");
		
	}
}
public class Car implements Vehicle {
    @Override
	public void go() {
        System.out.println("Move by Car");
    }
}
public class Travel {
	 Vehicle v;
	    
	    public Travel(Vehicle v) {
	        this.v = v;
	    }

	    void startCat() {
	        v.go();
	    }

}
