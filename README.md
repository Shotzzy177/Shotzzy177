-- Script de dinheiro infinito

-- Exemplo de variável de dinheiro
local dinheiro = 300000

function darDinheiroInfinito(300000)
    while true do
        dinheiro = math.huge -- Define dinheiro como infinito
        wait(0.1) -- Espera um pequeno intervalo antes da próxima atualização
    end
end

darDinheiroInfinito(300000) -- Chamando a função principal
