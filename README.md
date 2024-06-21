<div class="barra-iconos">
  <a href="#" class="icono-movil">
    <i class="fas fa-home"></i>
    <span>Inicio</span>
  </a>
  <a href="#" class="icono-movil">
    <i class="fas fa-shopping-basket"></i>
    <span>Productos</span>
  </a>
  <a href="#" class="icono-movil">
    <i class="fas fa-info-circle"></i>
    <span>Sobre Nosotros</span>
  </a>
  <a href="#" class="icono-movil">
    <i class="fas fa-phone"></i>
    <span>Contacto</span>
  </a>
  <a href="#" class="icono-movil">
    <i class="fas fa-truck"></i>
    <span>Envío</span>
  </a>
  <a href="#" class="icono-movil">
    <i class="fas fa-credit-card"></i>
    <span>Pago</span>
  </a>
  <a href="#" class="icono-movil">
    <i class="fas fa-user"></i>
    <span>Cuenta</span>
  </a>
</div>
.barra-iconos {
  display: flex;
  justify-content: center;
  background-color: #f2f2f2;
  padding: 10px 0;
  border-bottom: 1px solid #ddd;
}

.icono-movil {
  display: flex;
  flex-direction: column;
  align-items: center;
  color: #333;
  text-decoration: none;
  margin: 0 15px;
  transition: transform 0.3s;
}

.icono-movil i {
  font-size: 24px;
  margin-bottom: 5px;
}

.icono-movil span {
  font-size: 14px;
}

.icono-movil:hover {
  transform: translateY(-5px);
}
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css">
