
import React, { useState } from "react";
import { Card, CardContent } from "@/components/ui/card";
import { Button } from "@/components/ui/button";
import { Input } from "@/components/ui/input";
import { motion } from "framer-motion";

// CONFIGURE AQUI O IP DA SUA REDE
const ALLOWED_IP = "191.6.94.56"; // coloque o IP do seu roteador ou servidor local

export default function FranModasApp() {
  const [cart, setCart] = useState([]);
  const [search, setSearch] = useState("");

  const userIP = window.location.hostname;
  if (userIP !== ALLOWED_IP && userIP !== "localhost") {
    return (
      <div className="flex items-center justify-center h-screen bg-gray-100">
        <h1 className="text-2xl font-bold text-red-600">
          Acesso permitido apenas na rede interna da Fran Modas
        </h1>
      </div>
    );
  }

  const products = [
    { id: 1, name: "Vestido Floral", price: 129.9 },
    { id: 2, name: "Blusa Feminina", price: 59.9 },
    { id: 3, name: "Calça Jeans", price: 149.9 },
    { id: 4, name: "Conjunto Social", price: 199.9 },
  ];

  const filtered = products.filter((p) =>
    p.name.toLowerCase().includes(search.toLowerCase())
  );

  const addToCart = (product) => {
    setCart([...cart, product]);
  };

  const total = cart.reduce((acc, item) => acc + item.price, 0);

  return (
    <div className="p-6 bg-gray-50 min-h-screen">
      <motion.h1
        initial={{ opacity: 0, y: -20 }}
        animate={{ opacity: 1, y: 0 }}
        className="text-4xl font-bold text-center mb-6"
      >
        Fran Modas
      </motion.h1>

      <div className="max-w-md mx-auto mb-6">
        <Input
          placeholder="Pesquisar produto..."
          value={search}
          onChange={(e) => setSearch(e.target.value)}
        />
      </div>

      <div className="grid md:grid-cols-2 gap-6">
        {filtered.map((product) => (
          <Card key={product.id} className="rounded-2xl shadow-lg">
            <CardContent className="p-4">
              <h2 className="text-xl font-semibold">{product.name}</h2>
              <p className="text-lg mt-2">R$ {product.price.toFixed(2)}</p>
              <Button
                className="mt-4 w-full"
                onClick={() => addToCart(product)}
              >
                Adicionar ao Carrinho
              </Button>
            </CardContent>
          </Card>
        ))}
      </div>

      <div className="mt-10 max-w-md mx-auto bg-white p-6 rounded-2xl shadow-xl">
        <h2 className="text-2xl font-bold mb-4">Carrinho</h2>
        {cart.length === 0 ? (
          <p>Nenhum produto adicionado.</p>
        ) : (
          cart.map((item, index) => (
            <div key={index} className="flex justify-between">
              <span>{item.name}</span>
              <span>R$ {item.price.toFixed(2)}</span>
            </div>
          ))
        )}
        <hr className="my-4" />
        <h3 className="text-xl font-bold">Total: R$ {total.toFixed(2)}</h3>
      </div>
    </div>
  );
}
