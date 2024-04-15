# Polimorfismo

El polimorfismo es cuando una clase hija sobrescribe un método que le fue heredado. Por lo que el polimorfismo permite redefinir el comportamiento de la clase.

Sintaxis
Shape *shape1 = new Circle;
Shape *shape2 = new Rectangle;
Shape *shape3 = new Oval;

// Una función que toma una Shape de cualquier tipo derivado
void draw_shape(Shape* shape_ptr)
{
    shape_ptr->draw();
}


https://docs.hektorprofe.net/cpp/11-clases/06-polimorfismo-clases/
