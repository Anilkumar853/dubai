import React from "react";
import { Button } from "@/components/ui/button";
import { Card, CardContent } from "@/components/ui/card";
import { Phone, Mail, Globe } from "lucide-react";

export default function HomePage() {
  return (
    <div className="p-6 max-w-7xl mx-auto">
      <header className="text-center mb-10">
        <h1 className="text-4xl font-bold">FQ ALTAQANEIYA COMPUTER TRADING L.L.C</h1>
        <p className="text-xl mt-2 text-gray-600">Empowering Your Digital World.</p>
      </header>

      <section className="grid grid-cols-1 md:grid-cols-3 gap-6 mb-10">
        <Card>
          <CardContent className="p-4">
            <h2 className="text-xl font-semibold mb-2">Hardware Sales</h2>
            <p>We offer a wide range of branded computer hardware at competitive prices.</p>
          </CardContent>
        </Card>
        <Card>
          <CardContent className="p-4">
            <h2 className="text-xl font-semibold mb-2">Software Installation</h2>
            <p>Professional installation and licensing for all major software applications.</p>
          </CardContent>
        </Card>
        <Card>
          <CardContent className="p-4">
            <h2 className="text-xl font-semibold mb-2">IT Support</h2>
            <p>Reliable IT maintenance, troubleshooting, and technical assistance.</p>
          </CardContent>
        </Card>
      </section>

      <section className="mb-10">
        <h2 className="text-2xl font-bold mb-4">Product Catalog</h2>
        <p className="text-gray-700">Our full product catalog will include computers, accessories, spare parts, and more from all major brands.</p>
      </section>

      <section className="mb-10">
        <h2 className="text-2xl font-bold mb-4">Contact Us</h2>
        <div className="space-y-2">
          <p className="flex items-center gap-2"><Phone size={18} /> +971 567914384</p>
          <p className="flex items-center gap-2"><Mail size={18} /> computertradingllcfqaltaqaneiy@gmail.com</p>
          <p className="flex items-center gap-2"><Globe size={18} /> 57P7+2R2 - Marasi Dr - Business Bay - Dubai - UAE</p>
        </div>
        <Button className="mt-4 bg-green-500 hover:bg-green-600">Chat on WhatsApp</Button>
      </section>

      <footer className="text-center text-gray-500 mt-10">
        &copy; {new Date().getFullYear()} FQ ALTAQANEIYA COMPUTER TRADING L.L.C. All rights reserved.
      </footer>
    </div>
  );
}
