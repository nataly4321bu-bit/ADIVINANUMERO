 let numeroSecreto = Math.floor(Math.random() * 100) + 1;

    const input = document.getElementById("numero");
    const resultado = document.getElementById("resultado");

    document.getElementById("comprobar").addEventListener("click", () => {
      let valor = Number(input.value);

      if (!valor) {
        resultado.textContent = "Escribe un número válido";
        return;
      }

      if (valor === numeroSecreto) {
        resultado.textContent = "¡ADIVINASTE! ";
      } else if (valor > numeroSecreto) {
        resultado.textContent = "El número es menor ";
      } else {
        resultado.textContent = "El número es mayor ";
      }
    });

    document.getElementById("reiniciar").addEventListener("click", () => {
      numeroSecreto = Math.floor(Math.random() * 100) + 1;
      resultado.textContent = "";
      input.value = "";
    });
