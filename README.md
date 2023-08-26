- 👋 Hi, I’m @GuimaraesOFC
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
GuimaraesOFC/GuimaraesOFC is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
<!DOCTYPE html>
<html>

<head>
    <meta charset="UTF-8" />
    <title>Seu Título Aqui</title>
    <!-- Inclua o arquivo CSS do Tailwind aqui -->
    <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.16/dist/tailwind.min.css" rel="stylesheet">
    <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.16/dist/tailwind.min.css" rel="stylesheet">
    <link href="https://cdn.jsdelivr.net/npm/datepicker@1.0.10/dist/datepicker.min.css" rel="stylesheet">
    <script src="https://cdn.jsdelivr.net/npm/datepicker@1.0.10/dist/datepicker.min.js"></script>
    
 
</head>

<body class="bg-blue-100 min-h-screen flex items-center justify-center"> <!-- Estilo de fundo e centralização -->

    <div class="bg-white max-w-md p-6 rounded-md shadow-md"> <!-- Container para o formulário -->
        <div class="flex items-center justify-center ">
            <h1 class="text-2xl font-bold text-red-700">Formulário</h1>
          </div>
        <form>

            <div class="mb-4">
                <label for="nome" class="block text-gray-600">Nome:</label>
                <input type="text" id="nome" name="nome" autofocus required size="50" class="border border-gray-300 p-2 rounded-md w-full focus:outline-none focus:ring focus:border-blue-500">
            </div>

            <div class="mb-4">
                <label class="block text-green-600">Sexo:</label>
                <div class="flex space-x-4">
                    <label class="inline-flex items-center">
                        <input type="radio" id="masc" name="sexo" value="Masc" checked class="form-radio text-blue-700">
                        <span class="ml-2">Masculino</span>
                    </label>
                    <label class="inline-flex items-center">
                        <input type="radio" id="fem" name="sexo" value="Fem" class="form-radio text-pink-500">
                        <span class="ml-2">Feminino</span>
                    </label>
                    <label class="inline-flex items-center">
                        <input type="radio" id="outro" name="sexo" value="Outro" class="form-radio text-gray-500">
                        <span class="ml-2">Outro</span>
                    </label>
                </div>
            </div>
            

            <div class="mb-4 relative">
                <label for="marcaCarro" class="block text-blak-600">Marca de carro:</label>
                <select id="marcaCarro" name="marcaCarro" class="appearance-none bg-white border border-blue-500 text- bg-blue-500 py-2 px-4 pr-8 rounded-md w-full focus:outline-none focus:ring focus:border-blue-500">
                    <option value="volkswagen">Volkswagen</option>
                    <option value="ford">Ford</option>
                    <option value="gm" selected>GM</option>
                    <option value="audi">Audi</option>
                    <option value="audi">BMW</option>
                    <option value="audi">Fiat</option>
                </select>
                <div class="absolute inset-y-2 right-0 flex items-center pr-3 pointer-events-none">
                    <svg class="h-5 w-5 text-red-700" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor" aria-hidden="true">
                        <path fill-rule="evenodd" d="M9.293 4.293a1 1 0 011.414 0l5 5a1 1 0 01-1.414 1.414L10 6.414l-4.293 4.293a1 1 0 01-1.414-1.414l5-5z" clip-rule="evenodd" />
                    </svg>
                </div>
            </div>

            <div class="mb-4">
                <label for="senha" class="block text-green-600">Senha:</label>
                <input type="password" id="senha" name="senha" class="border border-gray-300 p-2 rounded-md w-full focus:outline-none focus:ring focus:border-blue-500">
            </div>

            <div class="mb-4">
                <label for="numero" class="block text-green-600">Número:</label>
                <input type="number" id="numero" name="numero" class="border border-gray-300 p-2 rounded-md w-full focus:outline-none focus:ring focus:border-blue-500">
            </div>

            <div class="mb-4">
                <label for="email" class="block text-green-600">Email:</label>
                <input type="email" id="email" name="email" class="border border-gray-300 p-2 rounded-md w-full focus:outline-none focus:ring focus:border-blue-500">
            </div>

            <div class="mb-4">
                <label for="telefone" class="block text-green-600">Telefone:</label>
                <input type="tel" id="telefone" name="telefone" class="border border-gray-300 p-2 rounded-md w-full focus:outline-none focus:ring focus:border-blue-500">
            </div>

            <div class="mb-4">
                <label for="dataNascimento" class="block text-green-600">Data de Nascimento:</label>
                <input type="text" id="dataNascimento" name="dataNascimento" class="border border-gray-300 p-2 rounded-md w-full focus:outline-none focus:ring focus:border-blue-500">
            
                <!-- JavaScript para inicializar o DatePicker.js -->
                <script>
                    const dataNascimentoInput = document.getElementById('dataNascimento');
                    const datepicker = new Datepicker(dataNascimentoInput, {
                        format: 'dd/mm/yyyy', // Formato da data
                        autohide: true, 
                    });
                </script>
            </div>

            <div class="mb-4">
                <input type="submit" value="Salvar" class="bg-pink-500 text-white px-4 py-2 rounded-md cursor-pointer">
            </div>

        </form>
    </div>
</body>


<div class="border border-gray-800">
    

</div>
