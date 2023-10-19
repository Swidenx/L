public class Ordenamiento {
    
    public void intercambio(int vector[]){
        for (int i =0;i < vector.length;i++){
            for (int j=i+1 ; j<vector.length;j++){
                if(vector[i]>vector[j]){
                    int aux= vector[i];
                    vector[i]= vector[j];
                    vector[j]= aux;
                }

            }

            
        }
        
    }

    public void seleccion(int vector[]){
        
        for (int i =0 ;i <original.length;i++){
            for (int j=i+1;j<original.length;j++){
                if(vector[i]>vector[j]){
                    vector[i]= vector[j];
                    vector[j]= aux;
                    
                }
                
            }
        }
    }
  
}


public class App {

    public static void main(String[] args) throws Exception {

        Ordenamiento ord = new Ordenamiento(); 

        int[] original = VectorUtil.generar(10);

        VectorUtil.imprimirVector(original);

        int v[]= VectorUtil.clonar(original);

        ord.intercambio(v);


        VectorUtil.imprimirVector(v);
        System.out.println();

        int v1[]= VectorUtil.clonar(original);

        ord.seleccion(v1);
        System.out.println();

        VectorUtil.imprimirVector(v1);
        

    
    }
}






import java.util.Random;

public class VectorUtil {

    public static int[] generar(int tamanio){
        Random rnd = new Random();
        
        int vector[] = new int[tamanio];
        for(int i = 0; i < tamanio; i++){
            vector[i] = rnd.nextInt(100);
        }
        return vector;
    }

    public static void imprimirVector(int vector[]){
        for(int j= 0; j < vector.length; j++){
            System.out.print(vector[j] + " ");
        }
        System.out.println();
    }
    public static int[] clonar(int original[]){
        int clon[]= new int [original.length];
        for (int i =0 ;i <original.length;i++){
        clon[i]=original[i];
        }
        return clon;


    }

    
}



