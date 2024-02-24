export default function Component() {
return (
<div id="DesktopRoot" className="bg-black w-full min-h-screen flex flex-col items-center justify-center text-white p-4">
<div className="mb-10">
<button className="bg-gray-800 px-6 py-2 rounded-md text-md mb-2">Anonymous</button>
<div className="grid grid-cols-4 gap-1">
<div className="h-2 w-2 rounded-full bg-gray-700"></div>
<div className="h-2 w-2 rounded-full bg-gray-700"></div>
<div className="h-2 w-2 rounded-full bg-gray-700"></div>
<div className="h-2 w-2 rounded-full bg-gray-700"></div>
</div>
</div>
<div className="max-w-lg mx-auto text-center">
<div className="mb-4 bg-gray-800 p-2 inline-block rounded-md">
<span className="text-yellow-400 text-sm">For Indian Users Only</span>
</div>
<h1 className="text-4xl font-bold mb-4">Start Posting Anonymously where no one will judge</h1>
<p className="text-gray-500 mb-10">Welcome to stranger discussion forum</p>
<button className="bg-gray-700 px-8 py-4 rounded-full text-lg font-medium hover:bg-gray-600 transition-colors">
Create Your Account
<span className="ml-2">→</span>
</button>
<p className="text-gray-500 text-sm mt-4">Already have account? <a href="#" className="text-blue-400 hover:underline">Login</a></p>
</div>
</div>
);
}
