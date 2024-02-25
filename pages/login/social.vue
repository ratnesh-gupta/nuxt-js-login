<template>
    <div class="flex items-center justify-center min-h-screen bg-gray-100">
        <div class="w-full max-w-md p-8 space-y-6 rounded-xl bg-white shadow-md">
            <h1 class="text-2xl font-bold text-center">Log in to your account</h1>
            <form class="space-y-6" action="#" method="POST">
                <div>
                    <label for="email" class="text-sm font-semibold">Email</label>
                    <input type="email" id="email" placeholder="Email" required
                        class="w-full p-2 mt-1 border rounded-md focus:border-blue-400 focus:outline-none focus:ring focus:ring-blue-300" />
                </div>
                <div>
                    <label for="password" class="text-sm font-semibold">Password</label>
                    <input type="password" id="password" placeholder="Password" required
                        class="w-full p-2 mt-1 border rounded-md focus:border-blue-400 focus:outline-none focus:ring focus:ring-blue-300" />
                </div>
                <div class="flex items-center justify-between">
                    <div class="flex items-center">
                        <input id="remember_me" type="checkbox"
                            class="w-4 h-4 border-gray-300 rounded focus:ring-blue-500" />
                        <label for="remember_me" class="ml-2 text-sm">Remember me</label>
                    </div>
                    <a href="#" class="text-sm text-blue-600 hover:underline">Forgot password?</a>
                </div>
                <button type="submit"
                    class="w-full py-2 text-white bg-blue-600 rounded-md hover:bg-blue-700 focus:outline-none focus:ring-2 focus:ring-blue-500 focus:ring-opacity-50">
                    Sign in
                </button>
            </form>
            <div class="relative pt-1">
                <div class="flex justify-center">
                    <span class="px-2 text-sm text-gray-500 bg-white">Or continue with</span>
                </div>
            </div>
            <button
                class="flex items-center justify-center w-full px-4 py-2 space-x-2 text-sm font-medium text-gray-600 bg-gray-100 border border-gray-300 rounded-md hover:bg-gray-200 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-gray-500"
                type="button">
                <img src="/img/google-icon.svg" alt="Google" class="w-5 h-5" />
                <span>Sign in with Google</span>
            </button>
            <button
                class="flex items-center justify-center w-full px-4 py-2 space-x-2 text-sm font-medium text-gray-600 bg-gray-100 border border-gray-300 rounded-md hover:bg-gray-200 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-gray-500"
                type="button">
                <img src="/img/github-icon.svg" alt="GitHub" class="w-5 h-5" />
                <span>Sign in with GitHub</span>
            </button>
        </div>
    </div>
</template>