# CarroProprio_combustivel
Abastecer e andar alguns quilometros

public class Carro {

    private float abastecer;
    private float mover;
    private float resultk;
    private double kmrodado;

  /*  public Carro(){
        this.resultl = (float) (mover / abastecer);
        this.resultk = (float) (resultl - abastecer);
    }
/*
    /**
     *
     */
    

    /**
     * @return the abastecer
     */
    public float getAbastecer() {
        return abastecer;
    }

    /**
     * @return the mover
     */
    public float getMover() {
        return mover;
    }
    /**
     * @param abastecer the abastecer to set
     */
    public void setAbastecer(float abastecer) {
        this.abastecer = abastecer;
        
    }

    /**
     * @param mover the mover to set
     */
    public void setMover(float mover) {
        this.mover = mover;
    }

    /**
     * @return the resultl
     */
    public float getResultl() {
        return resultk = mover / abastecer;
    }

    /**
     * @return the resultk
     */
    public float getResultk() {
        return abastecer - resultk;
    }

    /**
     * @return the kmroduado
     */
    public double getKmrodado() {
        return kmrodado = mover - resultk;
    }
  
    /**
     * @return the kmRodado
     */

}
