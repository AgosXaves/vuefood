<template>
    <div class="card shopping-cart my-4 ">
        <div class="card-header text-light">
            <i class="fa fa-shopping-cart mr-2" aria-hidden="true"></i>
            Carrinho de Compras
            <router-link class="btn bnt-sm btn-comprando" :to="{name:'products'}" >Continuar Comprando</router-link>
            <div class="clearfix"></div>
        </div>
        <div class="card-body">
          <!-- PRODUCT -->
          <div class="row align-items-center py-2">
            <div class="col-4 text-center">
              <div class="img-circle">
                <img class="img-responsive" src="imgs/acai.png" alt="prewiew" width="120" height="80">
              </div>
            </div>
            <div class="col-8 text-left">
              <h4 class="product-name"><strong>Açai Bomba</strong></h4>
              <h5 class="h6">Product description</h5>
              <div class="d-flex py-4 justify-content-between align-items-center">
                <div class="col-10 d-flex align-items-center p-0 ">
                    <h6><strong>R$ 12,99 <span class="text-muted">x</span></strong></h6>
                     <div class="quantity ml-4">
                        <input type="button" value="+" class="plus">
                        <input type="number" step="1" max="99" min="1" value="1" title="Qty" class="qty"
                               size="4">
                        <input type="button" value="-" class="minus">
                    </div>
                </div>
                <div class="col-2 col-sm-2 col-md-2 text-right">
                    <button type="button" class="btn btn-outline-danger btn-xs">
                        <i class="fa fa-trash" aria-hidden="true"></i>
                    </button>
                </div>
            </div>
            </div>
          </div>
          
          <hr>
          <!-- PRODUCT -->
          <div class="row align-items-center py-2">
            <div class="col-4 text-center">
              <div class="img-circle">
                <img class="img-responsive" src="imgs/pizza.png" alt="prewiew" width="120" height="80">
              </div>
            </div>
            <div class="col-8 text-left">
              <h4 class="product-name"><strong>Pizza Salgada</strong></h4>
              <h5 class="h6">Product description</h5>
              <div class="d-flex py-4 justify-content-between align-items-center">
                <div class="col-10 d-flex align-items-center p-0 ">
                    <h6><strong>R$ 12,99 <span class="text-muted">x</span></strong></h6>
                     <div class="quantity ml-4">
                        <input type="button" value="+" class="plus">
                        <input type="number" step="1" max="99" min="1" value="1" title="Qty" class="qty"
                               size="4">
                        <input type="button" value="-" class="minus">
                    </div>
                </div>
                <div class="col-2 col-sm-2 col-md-2 text-right">
                    <button type="button" class="btn btn-outline-danger btn-xs">
                        <i class="fa fa-trash" aria-hidden="true"></i>
                    </button>
                </div>
            </div>
            </div>
          </div>
          <!-- END PRODUCT -->
          <hr>
          <div class="cart-price text-red">
              Preço Total: <b>R$ 52,00</b>
          </div>
        </div>
        <!-- end card body -->
        <a href="" class="cart-finalizar">Finalizar</a>
    </div>
</template>