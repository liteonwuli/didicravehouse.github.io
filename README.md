# didicravehouse.github.io
Where cravings come to confess
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Didi's Crave House</title>

  <!-- Tailwind CDN -->
  <script src="https://cdn.tailwindcss.com"></script>

</head>
<body class="bg-gray-50 text-gray-900">

  <!-- HEADER -->
  <header class="bg-white shadow-sm">
    <div class="max-w-6xl mx-auto px-6 py-4 flex justify-between items-center">
      <h1 class="text-2xl font-bold">
        DIDI'S <span class="text-orange-500">CRAVE HOUSE</span>
      </h1>
      <a href="https://wa.me/2349160381811" target="_blank" class="bg-orange-500 text-white px-5 py-2 rounded-xl">
        Order on WhatsApp
      </a>
    </div>
  </header>

  <!-- HERO -->
  <section class="px-6 py-16 max-w-6xl mx-auto grid md:grid-cols-2 gap-10 items-center">
    <div>
      <h2 class="text-4xl font-bold">Where cravings come to confess</h2>
      <p class="mt-4 text-gray-600">Delicious Nigerian meals made fresh for you.</p>
    </div>

    <img
      src="https://images.unsplash.com/photo-1504674900247-0877df9cc836"
      class="rounded-2xl shadow-lg"
    />
  </section>

  <!-- MENU -->
  <section class="bg-white px-6 py-16">
    <div class="max-w-6xl mx-auto">
      <h2 class="text-3xl font-semibold text-center mb-12">Our Menu</h2>

      <div class="grid md:grid-cols-3 gap-8">

        <div class="bg-gray-50 p-6 rounded-2xl shadow">
          <h3 class="text-xl font-semibold mb-4">Soups</h3>
          <ul class="space-y-2 text-gray-600">
            <li>Egusi</li>
            <li>Ogbono</li>
            <li>Vegetable</li>
            <li>Okra</li>
            <li>Native</li>
          </ul>
        </div>

        <div class="bg-gray-50 p-6 rounded-2xl shadow">
          <h3 class="text-xl font-semibold mb-4">Toppings</h3>
          <ul class="space-y-2 text-gray-600">
            <li>Fried Chicken</li>
            <li>Beef</li>
            <li>Fish</li>
            <li>Plantain</li>
            <li>Turkey</li>
            <li>Extra Stew</li>
            <li>Extra Veggies</li>
          </ul>
        </div>

        <div class="bg-gray-50 p-6 rounded-2xl shadow">
          <h3 class="text-xl font-semibold mb-4">Main Dishes</h3>
          <ul class="space-y-2 text-gray-600">
            <li>Beef Dodo Combo</li>
            <li>Smokey Jollof Rice</li>
            <li>Native Rice</li>
            <li>Spaghetti Bolognese</li>
            <li>Stir Fried Noodles</li>
          </ul>
        </div>

      </div>
    </div>
  </section>

  <!-- PAYMENT -->
  <section class="bg-orange-50 px-6 py-16 text-center">
    <h2 class="text-3xl font-semibold">Payment Details</h2>
    <p class="mt-4 text-lg">Account Number: <strong>9160381811</strong></p>
    <p class="text-gray-600 mt-2">Transfer and send proof on WhatsApp</p>
  </section>

  <!-- ORDER FORM -->
  <section class="px-6 py-16">
    <div class="max-w-2xl mx-auto bg-white p-8 rounded-2xl shadow">
      <h2 class="text-2xl font-semibold text-center mb-6">Place Order</h2>

      <form onsubmit="submitOrder(event)">
        <input required placeholder="Your Name" class="w-full border p-3 rounded-xl mb-4" />
        <input required placeholder="Phone Number" class="w-full border p-3 rounded-xl mb-4" />
        <input required placeholder="Delivery Address" class="w-full border p-3 rounded-xl mb-4" />
        <textarea required placeholder="Your Order" class="w-full border p-3 rounded-xl mb-4"></textarea>

        <button class="w-full bg-orange-500 text-white py-3 rounded-xl">
          Submit Order
        </button>
      </form>
    </div>
  </section>

  <!-- CONTACT -->
  <section class="bg-white px-6 py-16 text-center">
    <h2 class="text-3xl font-semibold mb-6">Contact</h2>
    <p>Phone: +234 916 038 1811</p>
    <p>Location: Port Harcourt, Nigeria</p>
  </section>

  <!-- FOOTER -->
  <footer class="text-center py-8 text-sm text-gray-500">
    ©️ 2026 Didi's Crave House
  </footer>

  <script>
    function submitOrder(e) {
      e.preventDefault();
      alert("Order submitted! Send payment proof on WhatsApp.");
    }
  </script>

</body>
</html>
