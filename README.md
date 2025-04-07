Class Punto:
      def__init__(self, x, y):
            self.x = x
            self. y = y 

      def eje_x(self):
          return self.y == 0


      def eje_y(self):
          return self.x == 0

      def impresion(self):
           return f "({self.x}, {self.y})"


      def opuesto(self):
           return punt (-self.x, -self.y)


      def distancia_al_origen(self):
           return (self.x**2 + self.y**2) ** 0.5


      def mover(self, dx, dy):
          self.x += dx
          self.y += dy


      def__str__(self):
            return sel.impresion()
          

      
