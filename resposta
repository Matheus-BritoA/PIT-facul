function converterDataParaBrasileiro(dataISO) {
    return dataISO.replace(/(\d{4})-(\d{2})-(\d{2})/, '$3/$2/$1');
}

// Testes de Exemplo

const datasTeste = [
    "2025-02-07",
    "2024-12-25",
    "2023-07-14",
    "2022-01-01",
    "2021-09-03"
];

datasTeste.forEach(data => {
    console.log(`Data original: ${data} -> Data convertida: ${converterDataParaBrasileiro(data)}`);
});
