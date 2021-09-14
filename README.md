# ProductOfarray
public class ProductOfArray {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        // TODO code application logic here
        
        int[]arr=new int[]{2,5,6,7,8};
        int product=1;
            for (int i = 1; i<arr.length; i++)
            {
                product = product* arr[i];
            }
            System.out.println("product of all the elements of an array:"+product);
            
            }
                
    
    }
    
