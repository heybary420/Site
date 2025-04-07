"use client";

import { ArrowRight } from "lucide-react";

export default function XTrendPromo() {
  return (
    <main className="bg-white text-gray-900 min-h-screen flex flex-col items-center px-6 py-12">
      {/* Hero Section */}
      <section className="w-full max-w-5xl text-center mb-16">
        <h1 className="text-4xl md:text-5xl font-bold mb-4">Get Started with XTrend Speed</h1>
        <p className="text-lg text-gray-700 mb-6">
          Join one of the fastest-growing trading platforms and receive a welcome bonus using the referral code below.
        </p>
        <a
          href="https://xtrendspeed.com/s/Mby63i"
          target="_blank"
          rel="noopener noreferrer"
          className="inline-flex items-center gap-2 bg-blue-600 hover:bg-blue-700 text-white font-medium text-lg px-6 py-3 rounded-full shadow"
        >
          Use Code <strong className="ml-1">Mby63i</strong> <ArrowRight size={20} />
        </a>
      </section>

      {/* Benefits Section */}
      <section className="grid grid-cols-1 md:grid-cols-2 gap-8 max-w-5xl w-full mb-16">
        <div className="bg-blue-50 p-6 rounded-xl shadow">
          <h2 className="text-2xl font-semibold mb-2">Why Join XTrend Speed?</h2>
          <ul className="list-disc list-inside text-gray-700 space-y-1">
            <li>Zero commissions on trades</li>
            <li>Access to real-time market data</li>
            <li>Quick and secure transactions</li>
            <li>Simple, intuitive mobile platform</li>
          </ul>
        </div>
        <div className="bg-blue-50 p-6 rounded-xl shadow">
          <h2 className="text-2xl font-semibold mb-2">Steps to Start</h2>
          <ol className="list-decimal list-inside text-gray-700 space-y-1">
            <li>Click the button above to visit the app</li>
            <li>Download for iOS or Android</li>
            <li>Create your account and enter code <strong>Mby63i</strong></li>
            <li>Enjoy your bonus and start trading!</li>
          </ol>
        </div>
      </section>

      {/* Final Call to Action */}
      <section className="text-center max-w-4xl">
        <h2 className="text-3xl font-bold mb-4">Don’t Miss Out!</h2>
        <p className="text-gray-700 mb-6">
          Sign up with the referral code <strong>Mby63i</strong> and start your trading journey with an exclusive bonus.
        </p>
        <a
          href="https://xtrendspeed.com/s/Mby63i"
          target="_blank"
          rel="noopener noreferrer"
          className="inline-flex items-center gap-2 bg-blue-600 hover:bg-blue-700 text-white font-medium text-lg px-6 py-3 rounded-full shadow"
        >
          Join Now <ArrowRight size={20} />
        </a>
      </section>
    </main>
  );
}
