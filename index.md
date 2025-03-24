<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>The (open) Hub</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Pacifico&display=swap"
      rel="stylesheet"
    />
    <link
      href="https://cdnjs.cloudflare.com/ajax/libs/remixicon/4.6.0/remixicon.min.css"
      rel="stylesheet"
    />
    <script>
      tailwind.config = {
        theme: {
          extend: {
            colors: {
              primary: "#6B21A8",
              secondary: "#F3E8FF",
            },
            borderRadius: {
              none: "0px",
              sm: "4px",
              DEFAULT: "8px",
              md: "12px",
              lg: "16px",
              xl: "20px",
              "2xl": "24px",
              "3xl": "32px",
              full: "9999px",
              button: "8px",
            },
          },
        },
      };
    </script>
    <style>
      :where([class^="ri-"])::before { content: "\f3c2"; }
      .dark-card {
          background-color: rgba(0, 0, 0, 0.2);
          backdrop-filter: blur(10px);
      }
    </style>
  </head>
  <body class="bg-[#1a1a1a] text-white min-h-screen">
    <div class="max-w-4xl mx-auto p-8">
      <div class="flex items-center gap-4 mb-8">
        <div
          class="w-16 h-16 bg-primary rounded-lg flex items-center justify-center"
        >
          <span class="font-['Pacifico'] text-2xl">(open)</span>
        </div>
        <div>
          <h1 class="text-2xl font-bold mb-2">The (open) Hub</h1>
          <p class="flex items-center gap-2 text-gray-300">
            <i class="ri-map-pin-line"></i>
            We're a group of open-minded people, gathering to discuss
            non-monogamy & relationships
          </p>
        </div>
      </div>

      <section class="mb-12">
        <h2 class="text-xl font-semibold mb-6">Community</h2>
        <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
          <div class="dark-card p-6 rounded-lg">
            <h3 class="font-semibold mb-4">WhatsApp Community Group</h3>
            <div class="bg-white p-4 rounded-lg mb-4">
              <img
                src="https://public.readdy.ai/ai/img_res/ee17bb6bb84052dafb009c35eb5f6a8d.jpg"
                alt="WhatsApp QR Code"
                class="w-full"
              />
            </div>
            <a
              href="#"
              class="text-blue-400 hover:underline flex items-center gap-2"
            >
              <i class="ri-whatsapp-line"></i>
              Join our WhatsApp group
            </a>
          </div>

          <div class="dark-card p-6 rounded-lg">
            <h3 class="font-semibold mb-4">Follow Us on Instagram</h3>
            <p class="mb-4">Instagram: @theopenhub</p>
            <a
              href="#"
              class="text-blue-400 hover:underline flex items-center gap-2"
            >
              <i class="ri-instagram-line"></i>
              Follow on Instagram
            </a>
          </div>
        </div>
      </section>

      <section class="mb-12">
        <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
          <div class="dark-card p-6 rounded-lg">
            <h3 class="font-semibold mb-4">Events Calendar</h3>
            <a
              href="#"
              class="text-blue-400 hover:underline flex items-center gap-2"
            >
              <i class="ri-calendar-line"></i>
              View our calendar
            </a>
          </div>
          <div class="dark-card p-6 rounded-lg">
            <h3 class="font-semibold mb-4">The Buddy System</h3>
            <p class="mb-4">Find a buddy to go to events with 😊</p>
            <a
              href="#"
              class="text-blue-400 hover:underline flex items-center gap-2"
            >
              <i class="ri-user-add-line"></i>
              Register as a buddy
            </a>
          </div>
        </div>
      </section>

      <section class="mb-12">
        <h2 class="text-xl font-semibold mb-6">Give Us Feedback!</h2>
        <div class="dark-card p-6 rounded-lg">
          <a href="#" class="block mb-4 text-blue-400 hover:underline"
            >Feedback form (ENG)</a
          >
          <a href="#" class="block text-blue-400 hover:underline"
            >Formulário de feedback (PT)</a
          >
        </div>
      </section>
      <section class="mb-12">
        <h2 class="text-xl font-semibold mb-6">Resources</h2>
        <div class="dark-card p-6 rounded-lg">
          <ul class="space-y-4">
            <li>
              <a
                href="#"
                class="flex items-center gap-2 text-blue-400 hover:underline"
              >
                <i class="ri-file-list-line"></i>
                Community Guidelines
              </a>
            </li>
            <li>
              <a
                href="#"
                class="flex items-center gap-2 text-blue-400 hover:underline"
              >
                <i class="ri-heart-line"></i>
                Therapist recommendations
              </a>
            </li>
            <li>
              <a
                href="#"
                class="flex items-center gap-2 text-blue-400 hover:underline"
              >
                <i class="ri-mail-line"></i>
                2024 end-of-year message from Open Hub
              </a>
            </li>
          </ul>
        </div>
      </section>

      <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
        <section>
          <h2 class="text-xl font-semibold mb-6">Useful Links</h2>
          <div class="dark-card p-6 rounded-lg">
            <ul class="space-y-4">
              <li>
                <a href="#" class="text-blue-400 hover:underline"
                  >Free Sexual Health Testing</a
                >
              </li>
              <li>
                <a href="#" class="text-blue-400 hover:underline"
                  >Relationship Resources</a
                >
              </li>
              <li>
                <a href="#" class="text-blue-400 hover:underline"
                  >STARS Talk Framework</a
                >
              </li>
              <li>
                <a href="#" class="text-blue-400 hover:underline"
                  >Relationship Menu</a
                >
              </li>
            </ul>
          </div>
        </section>

        <section>
          <h2 class="text-xl font-semibold mb-6">Influencers to Follow</h2>
          <div class="dark-card p-6 rounded-lg">
            <ul class="space-y-4">
              <li>
                <a href="#" class="text-blue-400 hover:underline"
                  >@polyamlove</a
                >
              </li>
              <li>
                <a href="#" class="text-blue-400 hover:underline"
                  >@relationshipguru</a
                >
              </li>
              <li>
                <a href="#" class="text-blue-400 hover:underline">@lovecoach</a>
              </li>
            </ul>
          </div>
        </section>
      </div>
    </div>
  </body>
</html>
