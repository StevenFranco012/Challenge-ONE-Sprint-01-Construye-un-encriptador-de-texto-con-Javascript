# Challenge-ONE-Sprint-01-Construye-un-encriptador-de-texto-con-Javascript

Proyecto de Encriptación y Desencriptación
Este proyecto es una aplicación web que permite a los usuarios encriptar y desencriptar texto. La aplicación utiliza un conjunto específico de reglas para encriptar el texto, reemplazando ciertos caracteres por palabras específicas. La desencriptación realiza el proceso inverso, reemplazando las palabras encriptadas por los caracteres originales.

Funcionalidades
Encriptación de texto: Los usuarios pueden introducir texto en un campo de entrada y hacer clic en un botón para encriptar el texto. El texto encriptado se muestra en la interfaz de usuario.

Desencriptación de texto: Los usuarios también pueden desencriptar texto. Al introducir texto encriptado y hacer clic en un botón, el texto se desencripta y se muestra en la interfaz de usuario.

Código
El fragmento de código proporcionado muestra la funcionalidad de desencriptación. Cuando el usuario hace clic en el botón "Desencriptar", la aplicación recoge el valor del campo de entrada, lo desencripta utilizando la función decrypt, y muestra el texto desencriptado en la interfaz de usuario.

btnDesencriptar.addEventListener("click", function () {
  console.log(inputEncriptar.value);
  const decryptedText = decrypt(inputEncriptar.value);
  msjEncrypt.textContent = decryptedText;
  imgMsjEncryptSection.style.display = "none";
  msjEncryptSection.style.display = "block";
});


Cómo usar
Abre la aplicación en tu navegador web.
Introduce el texto que deseas encriptar o desencriptar en el campo de entrada correspondiente.
Haz clic en el botón "Encriptar" o "Desencriptar" según sea necesario.
El texto encriptado o desencriptado se mostrará en la interfaz de usuario.
