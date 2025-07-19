---
layout: plain
showToc: "false"
---
<section className="relative w-full min-h-screen flex flex-col items-center justify-center px-6 py-16 overflow-hidden">
  {/* Background image */}
  <div className="absolute inset-0">
    <img
      src="/@blackberry-garance/blog-template/_r/-/assets/background-1.jpg"
      alt="Background"
      className="w-full h-full object-cover"
    />
  </div>

  {/* Main content */}
  <div className="relative z-20 max-w-6xl w-full grid grid-cols-1 md:grid-cols-3 gap-8 text-[#363607]">
    {/* Left quote */}
    <div className="md:col-span-1 text-center md:text-left flex items-center justify-center">
      <p className="text-lg leading-relaxed max-w-sm">
        Botany isn’t loud. It doesn’t crash or flash. It waits. It teaches you to observe slowly — to notice the curve of a leaf, the way roots reach without eyes, the language of color in petals. In a world rushing to be noticed, plants ask nothing. And yet, they offer everything.
      </p>
    </div>

    {/* Center title */}
    <div className="md:col-span-1 flex flex-col items-center justify-center text-center">
      <h1 className="text-5xl font-extrabold cinzel"> </h1>
      <h1 className="text-5xl cinzel">Rooted &</h1>
      <h1 className="text-5xl cinzel">Wild</h1>
      <p className="text-lg mt-4">A blog about botany.</p>
    </div>

    {/* Right quote */}
    <div className="md:col-span-1 text-center md:text-right flex items-center justify-center">
      <p className="text-lg leading-relaxed max-w-sm">
        In the cracks of pavement and along forgotten fences, plants grow anyway. They don’t need perfect conditions — just space, light, and a little time. Botany reminds us that life adapts. Even when ignored, green things find a way to bloom.
      </p>
    </div>
  </div>
</section>


<section id="articles" className="py-24">
  <div className="mx-auto max-w-7xl px-4 sm:px-6 lg:px-8">
    <h2 className="font-manrope text-4xl font-bold text-gray-900 text-center mb-16">My latest articles</h2>

    <div className="flex justify-center gap-y-8 lg:gap-y-0 flex-wrap md:flex-wrap lg:flex-nowrap lg:flex-row lg:justify-between lg:gap-x-8">
      {/* Blog Card 1 */}

      <div className="group w-full max-lg:max-w-xl lg:w-1/3 border border-[#A2A454] rounded-2xl transition-all duration-300 hover:bg-[#DAD6B0]">
        <div className="flex items-center">
          <img src="/@blackberry-garance/blog-template/_r/-/assets/urban-botany.jpg" alt="urban botany" className="rounded-t-2xl w-full object-cover" />
        </div>

        <div className="p-4 lg:p-6 rounded-b-2xl">
          <span className="text-[#A2A454] font-medium mb-3 block">Jun 03, 2025</span>
          <h4 className="text-xl text-gray-900 font-medium leading-8 mb-5">Urban Botany: How to Identify Plants Growing Through Sidewalk Cracks</h4>
          <p className="text-gray-500 leading-6 mb-10">Because nature doesn’t care about your concrete.</p>
          <a href="/blog/Urban Botany.md" className="cursor-pointer text-lg text-[#A2A454] font-semibold"> Read more.. </a>
        </div>
      </div>

      {/* Blog Card 2 */}

      <div className="group w-full max-lg:max-w-xl lg:w-1/3 border border-[#A2A454] rounded-2xl transition-all duration-300 hover:bg-[#DAD6B0]">
        <div className="flex items-center">
          <img src="/@blackberry-garance/blog-template/_r/-/assets/pexels-karolina-grabowska-4750274.jpg" alt="watering" className="rounded-t-2xl w-full object-cover" />
        </div>

        <div className="p-4 lg:p-6 rounded-b-2xl">
          <span className="text-[#A2A454] font-medium mb-3 block">May 28, 2025</span>
          <h4 className="text-xl text-gray-900 font-medium leading-8 mb-5">The Ultimate Guide to Watering — It’s Not Just About the Schedule</h4>
          <p className="text-gray-500 leading-6 mb-10">Because plants don’t wear watches, and neither should your watering can.</p>
          <a href="#" className="cursor-pointer text-lg text-[#A2A454] font-semibold"> Read more.. </a>
        </div>
      </div>

      {/* Blog Card 3 */}

      <div className="group w-full max-lg:max-w-xl lg:w-1/3 border border-[#A2A454] rounded-2xl transition-all duration-300 hover:bg-[#DAD6B0]">
        <div className="flex items-center">
          <img src="/@blackberry-garance/blog-template/_r/-/assets/wild-flowers.jpg" alt="wild flowers" className="rounded-t-2xl w-full object-cover" />
        </div>

        <div className="p-4 lg:p-6 rounded-b-2xl">
          <span className="text-[#A2A454] font-medium mb-3 block">Mar 15, 2025</span>
          <h4 className="text-xl text-gray-900 font-medium leading-8 mb-5">10 Wildflowers You’re Walking Past Without Noticing</h4>
          <p className="text-gray-500 leading-6 mb-10">10 wildflowers hiding in plain sight — learn their names and start noticing the beauty blooming underfoot.</p>
          <a href="#" className="cursor-pointer text-lg text-[#A2A454] font-semibold"> Read more.. </a>
        </div>
      </div>
    </div>
    <a href="/blog/README" className="mt-16 cursor-pointer border border-[#A2A454] shadow-sm rounded-full py-3.5 px-7 w-52 flex justify-center items-center text-gray-900 font-semibold mx-auto transition-all duration-300 hover:bg-[#DAD6B0]">View All</a>
  </div>
</section>
