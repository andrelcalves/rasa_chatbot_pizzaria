## caminho_01
* greet
  - say_greet
* order_pizza
  - say_do_order

## caminho_02
* greet
  - say_greet
* list_size
  - say_list_sizes
* order_pizza
  - say_do_order

## caminho_03
* greet
  - say_greet
* order_pizza{"size": "grande", "tops": "calabresa"}
  - confirm_order
  
## caminho_04
* greet
  - say_greet
* order_pizza{"tops": "atum"}
  - ask_size
* order_pizza{"size": "média"}
  - confirm_order
  
## caminho_05
* greet
  - say_greet
* order_pizza{"size": "pequena"}
  - ask_tops
* order_pizza{"tops": "calabresa"}
  - confirm_order

## caminho_06
* list_tops
  - say_list_tops
* order_pizza{"tops": "atum"}
  - ask_size
* order_pizza{"size": "média"}
  - confirm_order

## caminho_010
* thankyou
  - dizer_despedida