************************************
************************************
******       BRANDON         *******
*** Discord : Monsieur Lee#8444 ****
************************************
************************************
******   CELO - PLATZI       *******
************************************
************************************


Hola. Muchas gracias a los docentes de platzi y la comunidad de CELO por permitirnos construir sobre la red de celo. 
De igual forma por los conocimientos técnicos asociados al desarrollo y despliegue de contratos inteligentes con el lenguaje solidity. 


Como entregable del programa desarrollé una UX en la cual se pudieran aglomerar distintos actores del sistema CRIPTO. 

El siguiente link los dirigirá a la presentación de mi idea usando blockchain celo y el despliegue de contratos inteligentes.  

--------------------------------------------------
https://my.visme.co/view/vd7ne66z-ne12merwy3nwl79x
--------------------------------------------------


De igual forma dejo una copia del contrato inteligente usado en la presentación y el ID del contrato desplegado en la red. 


-----------------------------------------------------------------------------
-------------------------  SOLIDIY CODE -------------------------------------


// SPDX-License-Identifier: MIT
pragma solidity ^0.8.4;

// Importar paquetes del repositorio de openzeppelin
import "@openzeppelin/contracts/token/ERC20/ERC20.sol";
import "@openzeppelin/contracts/access/Ownable.sol";

/ Declaración del contrato como instancia de ERC20 con los parámetros iniciales
// Nombre y símbolo del token
contract Festival is ERC20, Ownable, ERC20Burnable, {
    // Declaración del constructor  
    constructor() ERC20("FIESTA", "FST") {
        
        // El emisor del contrato recibirá los tokens iniciales
        _mint(msg.sender, 1000000 * 10 ** decimals());
    }
    
    // Se habilita la función mint para poder crear más token según la necesidad
    function mint(address to, uint256 amount) public onlyOwner {
        _mint(to, amount);
    }
}

---------------------------------------------------------------------------
------------------------  CONTRATO ----------------------------------------

Usar el explorador de bloques de la red alfajores. 

contract ID :  0xb36476b9780c0144CaE5D8e5b3823fb1E8F8ffc7

------------------------                ------------------------------------



Cualquier inquietud con gusto la responderé al DM de github o Discord. 

https://github.com/vrokolee
Discord: Monsieur Lee#8444






