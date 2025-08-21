                        Trading and Services
                            </h1>
                            <p class="text-xl md:text-2xl text-gray-300 mb-12 font-medium">
                                Your Professional Services Connection Platform
                            </p>
                            
                            <!-- Two Main Options -->
                            <div class="grid grid-cols-1 md:grid-cols-2 gap-8 max-w-4xl mx-auto">
                                <!-- Job Seekers -->
                                <div class="bg-gray-900 p-8 rounded-2xl golden-border hover-golden transition-all cursor-pointer" onclick="registerAs('job-seeker')">
                                    <div class="text-6xl mb-6">👨‍💼</div>
                                    <h2 class="text-2xl font-bold golden-text mb-4">Job Seekers</h2>
                                    <p class="text-gray-300 mb-6 font-medium">Register your profile and upload your CV to connect with potential employers.</p>
                                    <button class="golden-gradient text-black px-8 py-3 rounded-full font-bold text-lg w-full hover-golden transition-all">
                                        Register Now
                                    </button>
                                </div>
                                
                                <!-- Service Seekers -->
                                <div class="bg-gray-900 p-8 rounded-2xl golden-border hover-golden transition-all cursor-pointer" onclick="registerAs('service-seeker')">
                                    <div class="text-6xl mb-6">🏢</div>
                                    <h2 class="text-2xl font-bold golden-text mb-4">Service Seekers</h2>
                                    <p class="text-gray-300 mb-6 font-medium">Looking for professional services? Submit your requirements and we will connect you with qualified providers.</p>
                                    <button class="golden-gradient text-black px-8 py-3 rounded-full font-bold text-lg w-full hover-golden transition-all">
                                        Submit Enquiry
                                    </button>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>

            <!-- Register Page -->
            <div id="registerPage" class="page-content hidden">
                <div class="max-w-2xl mx-auto px-4 sm:px-6 lg:px-8 py-12">
                    <div class="bg-gray-900 p-8 rounded-2xl golden-border">
                        <h2 class="text-3xl font-bold golden-text mb-8 text-center">Register Now</h2>
                        <!-- Job Seeker Form -->
                        <form id="jobSeekerForm" class="space-y-6 hidden">
                            <h3 class="text-xl font-bold text-yellow-400 mb-4">Job Seeker Registration</h3>
                            <div>
                                <label class="block text-yellow-400 font-semibold mb-2">Full Name *</label>
                                <input type="text" id="jobSeekerName" required class="w-full bg-white text-black border-2 border-yellow-400 rounded-lg px-4 py-3 focus:ring-2 focus:ring-yellow-400 focus:border-transparent font-medium">
                            </div>
                            <div>
                                <label class="block text-yellow-400 font-semibold mb-2">Contact Number *</label>
                                <input type="tel" id="jobSeekerPhone" required class="w-full bg-white text-black border-2 border-yellow-400 rounded-lg px-4 py-3 focus:ring-2 focus:ring-yellow-400 focus:border-transparent font-medium">
                            </div>
                            <div>
                                <label class="block text-yellow-400 font-semibold mb-2">Email Address *</label>
                                <input type="email" id="jobSeekerEmail" required class="w-full bg-white text-black border-2 border-yellow-400 rounded-lg px-4 py-3 focus:ring-2 focus:ring-yellow-400 focus:border-transparent font-medium">
                            </div>
                            <div>
                                <label class="block text-yellow-400 font-semibold mb-2">Upload CV (PDF/DOC, Max 5MB) *</label>
                                <input type="file" id="jobSeekerCV" accept=".pdf,.doc,.docx" required class="w-full bg-white text-black border-2 border-yellow-400 rounded-lg px-4 py-3 focus:ring-2 focus:ring-yellow-400 focus:border-transparent font-medium file:mr-4 file:py-2 file:px-4 file:rounded-full file:border-0 file:text-sm file:font-semibold file:bg-yellow-400 file:text-black hover:file:bg-yellow-500">
                                <p class="text-sm text-gray-400 mt-1">Supported formats: PDF, DOC, DOCX (Maximum 5MB)</p>
                            </div>
                            <button type="submit" class="w-full golden-gradient text-black py-4 rounded-lg font-bold text-lg hover-golden transition-all">
                                Register Now
                            </button>
                        </form>

                        <!-- Service Seeker Form -->
                        <form id="serviceSeekerForm" class="space-y-6 hidden">
                            <h3 class="text-xl font-bold text-yellow-400 mb-4">Service Enquiry</h3>
                            <div>
                                <label class="block text-yellow-400 font-semibold mb-2">Name *</label>
                                <input type="text" id="serviceSeekerName" required class="w-full bg-white text-black border-2 border-yellow-400 rounded-lg px-4 py-3 focus:ring-2 focus:ring-yellow-400 focus:border-transparent font-medium">
                            </div>
                            <div>
                                <label class="block text-yellow-400 font-semibold mb-2">Contact Number *</label>
                                <input type="tel" id="serviceSeekerPhone" required class="w-full bg-white text-black border-2 border-yellow-400 rounded-lg px-4 py-3 focus:ring-2 focus:ring-yellow-400 focus:border-transparent font-medium">
                            </div>
                            <div>
                                <label class="block text-yellow-400 font-semibold mb-2">Email *</label>
                                <input type="email" id="serviceSeekerEmail" required class="w-full bg-white text-black border-2 border-yellow-400 rounded-lg px-4 py-3 focus:ring-2 focus:ring-yellow-400 focus:border-transparent font-medium">
                            </div>
                            <div>
                                <label class="block text-yellow-400 font-semibold mb-2">Select Category *</label>
                                <select id="serviceSeekerCategory" required class="w-full bg-white text-black border-2 border-yellow-400 rounded-lg px-4 py-3 focus:ring-2 focus:ring-yellow-400 focus:border-transparent font-medium">
                                    <option value="">Select Service Category</option>
                                    <option value="construction">Construction & Building</option>
                                    <option value="electrical">Electrical Services</option>
                                    <option value="plumbing">Plumbing Services</option>
                                    <option value="cleaning">Cleaning Services</option>
                                    <option value="maintenance">Maintenance & Repair</option>
                                    <option value="painting">Painting & Decoration</option>
                                    <option value="landscaping">Landscaping & Gardening</option>
                                    <option value="security">Security Services</option>
                                    <option value="catering">Catering & Food Services</option>
                                    <option value="transportation">Transportation & Logistics</option>
                                    <option value="it-services">IT & Technical Services</option>
                                    <option value="consulting">Business Consulting</option>
                                    <option value="legal">Legal Services</option>
                                    <option value="accounting">Accounting & Finance</option>
                                    <option value="marketing">Marketing & Advertising</option>
                                    <option value="healthcare">Healthcare Services</option>
                                    <option value="education">Education & Training</option>
                                    <option value="event-management">Event Management</option>
                                    <option value="photography">Photography & Videography</option>
                                    <option value="other">Other Services</option>
                                </select>
                            </div>
                            <div>
                                <label class="block text-yellow-400 font-semibold mb-2">Service Description *</label>
                                <textarea id="serviceSeekerDescription" required rows="4" class="w-full bg-white text-black border-2 border-yellow-400 rounded-lg px-4 py-3 focus:ring-2 focus:ring-yellow-400 focus:border-transparent font-medium" placeholder="Describe your service requirements in detail..."></textarea>
                            </div>
                            <button type="submit" class="w-full golden-gradient text-black py-4 rounded-lg font-bold text-lg hover-golden transition-all">
                                Submit Enquiry
                            </button>
                        </form>
                    </div>
                </div>
            </div>

            <!-- Ads Page -->
            <div id="adsPage" class="page-content hidden">
                <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8 py-12">
                    <h2 class="text-3xl font-bold golden-text mb-8 text-center">Current Opportunities</h2>
                    <div id="adsContainer" class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">
                        <!-- Ads will be populated here -->
                    </div>
                </div>
            </div>

            <!-- Contact Page -->
            <div id="contactPage" class="page-content hidden">
                <div class="max-w-4xl mx-auto px-4 sm:px-6 lg:px-8 py-12">
                    <div class="bg-gray-900 p-8 rounded-2xl golden-border">
                        <h2 class="text-3xl font-bold golden-text mb-8 text-center">Contact Us</h2>
                        <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
                            <div class="space-y-6">
                                <div>
                                    <h3 class="text-xl font-bold text-yellow-400 mb-4">Get in Touch</h3>
                                    <div class="space-y-4">
                                        <a href="tel:70157775" class="flex items-center space-x-3 text-white hover:text-yellow-400 transition-colors">
                                            <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 20 20">
                                                <path d="M2 3a1 1 0 011-1h2.153a1 1 0 01.986.836l.74 4.435a1 1 0 01-.54 1.06l-1.548.773a11.037 11.037 0 006.105 6.105l.774-1.548a1 1 0 011.059-.54l4.435.74a1 1 0 01.836.986V17a1 1 0 01-1 1h-2C7.82 18 2 12.18 2 5V3z"/>
                                            </svg>
                                            <span class="font-semibold">70157775</span>
                                        </a>
                                        <a href="tel:80837778" class="flex items-center space-x-3 text-white hover:text-yellow-400 transition-colors">
                                            <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 20 20">
                                                <path d="M2 3a1 1 0 011-1h2.153a1 1 0 01.986.836l.74 4.435a1 1 0 01-.54 1.06l-1.548.773a11.037 11.037 0 006.105 6.105l.774-1.548a1 1 0 011.059-.54l4.435.74a1 1 0 01.836.986V17a1 1 0 01-1 1h-2C7.82 18 2 12.18 2 5V3z"/>
                                            </svg>
                                            <span class="font-semibold">80837778</span>
                                        </a>
                                        <a href="mailto:tradehubqatar@gmail.com" class="flex items-center space-x-3 text-white hover:text-yellow-400 transition-colors">
                                            <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 8l7.89 4.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"></path>
                                            </svg>
                                            <span class="font-semibold">tradehubqatar@gmail.com</span>
                                        </a>
                                        <a href="https://www.tradehubqatar.com" target="_blank" class="flex items-center space-x-3 text-white hover:text-yellow-400 transition-colors">
                                            <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M21 12a9 9 0 01-9 9m9-9a9 9 0 00-9-9m9 9H3m9 9v-9m0-9v9"></path>
                                            </svg>
                                            <span class="font-semibold">www.tradehubqatar.com</span>
                                        </a>
                                    </div>
                                </div>
                            </div>
                            <div>
                                <h3 class="text-xl font-bold text-yellow-400 mb-4">Business Hours</h3>
                                <div class="space-y-2 text-gray-300">
                                    <p><span class="font-semibold">Sunday - Thursday:</span> 9 AM - 5 PM</p>
                                    <p><span class="font-semibold">Friday:</span> Closed</p>
                                </div>
                                
                                <div class="mt-8">
                                    <h3 class="text-xl font-bold text-yellow-400 mb-4">Send Inquiry</h3>
                                    <form id="inquiryForm" class="space-y-4">
                                        <input type="text" id="inquiryName" required placeholder="Your Name" class="w-full bg-white text-black border-2 border-yellow-400 rounded-lg px-4 py-3 focus:ring-2 focus:ring-yellow-400 focus:border-transparent font-medium">
                                        <input type="email" id="inquiryEmail" required placeholder="Your Email" class="w-full bg-white text-black border-2 border-yellow-400 rounded-lg px-4 py-3 focus:ring-2 focus:ring-yellow-400 focus:border-transparent font-medium">
                                        <textarea id="inquiryMessage" required rows="4" placeholder="Your Message" class="w-full bg-white text-black border-2 border-yellow-400 rounded-lg px-4 py-3 focus:ring-2 focus:ring-yellow-400 focus:border-transparent font-medium"></textarea>
                                        <button type="submit" class="w-full golden-gradient text-black py-3 rounded-lg font-bold hover-golden transition-all">
                                            Submit Inquiry
                                        </button>
                                    </form>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>

            <!-- Share Page -->
            <div id="sharePage" class="page-content hidden">
                <div class="max-w-2xl mx-auto px-4 sm:px-6 lg:px-8 py-12">
                    <div class="bg-gray-900 p-8 rounded-2xl golden-border text-center">
                        <h2 class="text-3xl font-bold golden-text mb-8">Share Trade Hub</h2>
                        <p class="text-gray-300 mb-8 font-medium">Share our app with your network and help others find opportunities!</p>
                        <div class="grid grid-cols-2 md:grid-cols-3 gap-4">
                            <button onclick="shareVia('whatsapp')" class="social-icon bg-green-600 text-white p-4 rounded-lg hover:bg-green-700 transition-all font-semibold">
                                <svg class="w-8 h-8 mx-auto mb-2" fill="currentColor" viewBox="0 0 24 24">
                                    <path d="M17.472 14.382c-.297-.149-1.758-.867-2.03-.967-.273-.099-.471-.148-.67.15-.197.297-.767.966-.94 1.164-.173.199-.347.223-.644.075-.297-.15-1.255-.463-2.39-1.475-.883-.788-1.48-1.761-1.653-2.059-.173-.297-.018-.458.13-.606.134-.133.298-.347.446-.52.149-.174.198-.298.298-.497.099-.198.05-.371-.025-.52-.075-.149-.669-1.612-.916-2.207-.242-.579-.487-.5-.669-.51-.173-.008-.371-.01-.57-.01-.198 0-.52.074-.792.372-.272.297-1.04 1.016-1.04 2.479 0 1.462 1.065 2.875 1.213 3.074.149.198 2.096 3.2 5.077 4.487.709.306 1.262.489 1.694.625.712.227 1.36.195 1.871.118.571-.085 1.758-.719 2.006-1.413.248-.694.248-1.289.173-1.413-.074-.124-.272-.198-.57-.347m-5.421 7.403h-.004a9.87 9.87 0 01-5.031-1.378l-.361-.214-3.741.982.998-3.648-.235-.374a9.86 9.86 0 01-1.51-5.26c.001-5.45 4.436-9.884 9.888-9.884 2.64 0 5.122 1.03 6.988 2.898a9.825 9.825 0 012.893 6.994c-.003 5.45-4.437 9.884-9.885 9.884m8.413-18.297A11.815 11.815 0 0012.05 0C5.495 0 .16 5.335.157 11.892c0 2.096.547 4.142 1.588 5.945L.057 24l6.305-1.654a11.882 11.882 0 005.683 1.448h.005c6.554 0 11.89-5.335 11.893-11.893A11.821 11.821 0 0020.885 3.488"/>
                                </svg>
                                WhatsApp
                            </button>
                            <button onclick="shareVia('facebook')" class="social-icon bg-blue-600 text-white p-4 rounded-lg hover:bg-blue-700 transition-all font-semibold">
                                <svg class="w-8 h-8 mx-auto mb-2" fill="currentColor" viewBox="0 0 24 24">
                                    <path d="M24 12.073c0-6.627-5.373-12-12-12s-12 5.373-12 12c0 5.99 4.388 10.954 10.125 11.854v-8.385H7.078v-3.47h3.047V9.43c0-3.007 1.792-4.669 4.533-4.669 1.312 0 2.686.235 2.686.235v2.953H15.83c-1.491 0-1.956.925-1.956 1.874v2.25h3.328l-.532 3.47h-2.796v8.385C19.612 23.027 24 18.062 24 12.073z"/>
                                </svg>
                                Facebook
                            </button>
                            <button onclick="shareVia('instagram')" class="social-icon bg-pink-600 text-white p-4 rounded-lg hover:bg-pink-700 transition-all font-semibold">
                                <svg class="w-8 h-8 mx-auto mb-2" fill="currentColor" viewBox="0 0 24 24">
                                    <path d="M12 2.163c3.204 0 3.584.012 4.85.07 3.252.148 4.771 1.691 4.919 4.919.058 1.265.069 1.645.069 4.849 0 3.205-.012 3.584-.069 4.849-.149 3.225-1.664 4.771-4.919 4.919-1.266.058-1.644.07-4.85.07-3.204 0-3.584-.012-4.849-.07-3.26-.149-4.771-1.699-4.919-4.92-.058-1.265-.07-1.644-.07-4.849 0-3.204.013-3.583.07-4.849.149-3.227 1.664-4.771 4.919-4.919 1.266-.057 1.645-.069 4.849-.069zm0-2.163c-3.259 0-3.667.014-4.947.072-4.358.2-6.78 2.618-6.98 6.98-.059 1.281-.073 1.689-.073 4.948 0 3.259.014 3.668.072 4.948.2 4.358 2.618 6.78 6.98 6.98 1.281.058 1.689.072 4.948.072 3.259 0 3.668-.014 4.948-.072 4.354-.2 6.782-2.618 6.979-6.98.059-1.28.073-1.689.073-4.948 0-3.259-.014-3.667-.072-4.947-.196-4.354-2.617-6.78-6.979-6.98-1.281-.059-1.69-.073-4.949-.073zm0 5.838c-3.403 0-6.162 2.759-6.162 6.162s2.759 6.163 6.162 6.163 6.162-2.759 6.162-6.163c0-3.403-2.759-6.162-6.162-6.162zm0 10.162c-2.209 0-4-1.79-4-4 0-2.209 1.791-4 4-4s4 1.791 4 4c0 2.21-1.791 4-4 4zm6.406-11.845c-.796 0-1.441.645-1.441 1.44s.645 1.44 1.441 1.44c.795 0 1.439-.645 1.439-1.44s-.644-1.44-1.439-1.44z"/>
                                </svg>
                                Instagram
                            </button>
                            <button onclick="shareVia('linkedin')" class="social-icon bg-blue-800 text-white p-4 rounded-lg hover:bg-blue-900 transition-all font-semibold">
                                <svg class="w-8 h-8 mx-auto mb-2" fill="currentColor" viewBox="0 0 24 24">
                                    <path d="M20.447 20.452h-3.554v-5.569c0-1.328-.027-3.037-1.852-3.037-1.853 0-2.136 1.445-2.136 2.939v5.667H9.351V9h3.414v1.561h.046c.477-.9 1.637-1.85 3.37-1.85 3.601 0 4.267 2.37 4.267 5.455v6.286zM5.337 7.433c-1.144 0-2.063-.926-2.063-2.065 0-1.138.92-2.063 2.063-2.063 1.14 0 2.064.925 2.064 2.063 0 1.139-.925 2.065-2.064 2.065zm1.782 13.019H3.555V9h3.564v11.452zM22.225 0H1.771C.792 0 0 .774 0 1.729v20.542C0 23.227.792 24 1.771 24h20.451C23.2 24 24 23.227 24 22.271V1.729C24 .774 23.2 0 22.222 0h.003z"/>
                                </svg>
                                LinkedIn
                            </button>
                            <button onclick="shareVia('twitter')" class="social-icon bg-sky-500 text-white p-4 rounded-lg hover:bg-sky-600 transition-all font-semibold">
                                <svg class="w-8 h-8 mx-auto mb-2" fill="currentColor" viewBox="0 0 24 24">
                                    <path d="M18.244 2.25h3.308l-7.227 8.26 8.502 11.24H16.17l-5.214-6.817L4.99 21.75H1.68l7.73-8.835L1.254 2.25H8.08l4.713 6.231zm-1.161 17.52h1.833L7.084 4.126H5.117z"/>
                                </svg>
                                Twitter/X
                            </button>
                            <button onclick="copyAppLink()" class="social-icon golden-gradient text-black p-4 rounded-lg hover-golden transition-all font-bold">
                                <svg class="w-8 h-8 mx-auto mb-2" fill="currentColor" viewBox="0 0 24 24">
                                    <path d="M13.19 8.688a4.5 4.5 0 0 1 1.242 7.244l-4.5 4.5a4.5 4.5 0 0 1-6.364-6.364l1.757-1.757m13.35-.622 1.757-1.757a4.5 4.5 0 0 0-6.364-6.364l-4.5 4.5a4.5 4.5 0 0 0 1.242 7.244"/>
                                </svg>
                                Copy Link
                            </button>
                        </div>
                    </div>
                </div>
            </div>

            <!-- Admin Page -->
            <div id="adminPage" class="page-content hidden">
                <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8 py-12">
                    <!-- Admin Login -->
                    <div id="adminLogin" class="max-w-md mx-auto">
                        <div class="bg-gray-900 p-8 rounded-2xl golden-border">
                            <h2 class="text-3xl font-bold golden-text mb-8 text-center">Admin Access</h2>
                            <form id="adminLoginForm" class="space-y-6">
                                <div>
                                    <label class="block text-yellow-400 font-semibold mb-2">Admin Password</label>
                                    <input type="password" id="adminPassword" required class="w-full bg-white text-black border-2 border-yellow-400 rounded-lg px-4 py-3 focus:ring-2 focus:ring-yellow-400 focus:border-transparent font-medium">
                                </div>
                                <button type="submit" class="w-full golden-gradient text-black py-4 rounded-lg font-bold text-lg hover-golden transition-all">
                                    Access Admin Panel
                                </button>
                            </form>
                        </div>
                    </div>

                    <!-- Admin Panel -->
                    <div id="adminPanel" class="hidden">
                        <div class="bg-gray-900 p-8 rounded-2xl golden-border">
                            <div class="flex justify-between items-center mb-8">
                                <h2 class="text-3xl font-bold golden-text">Admin Panel</h2>
                                <button onclick="logoutAdmin()" class="bg-red-600 text-white px-4 py-2 rounded-lg hover:bg-red-700 transition-colors font-semibold">
                                    Logout
                                </button>
                            </div>

                            <!-- Admin Navigation -->
                            <div class="flex flex-wrap gap-4 mb-8">
                                <button onclick="showAdminSection('registrations')" class="admin-nav-btn golden-gradient text-black px-6 py-3 rounded-lg font-bold hover-golden transition-all">
                                    View Registrations
                                </button>
                                <button onclick="showAdminSection('content')" class="admin-nav-btn bg-gray-700 text-white px-6 py-3 rounded-lg font-bold hover:bg-gray-600 transition-all">
                                    Edit Content
                                </button>
                                <button onclick="showAdminSection('ads')" class="admin-nav-btn bg-gray-700 text-white px-6 py-3 rounded-lg font-bold hover:bg-gray-600 transition-all">
                                    Manage Ads
                                </button>
                                <button onclick="showAdminSection('settings')" class="admin-nav-btn bg-gray-700 text-white px-6 py-3 rounded-lg font-bold hover:bg-gray-600 transition-all">
                                    Settings
                                </button>
                            </div>

                            <!-- Admin Sections -->
                            <div id="adminRegistrations" class="admin-section">
                                <h3 class="text-2xl font-bold text-yellow-400 mb-6">User Registrations</h3>
                                <div class="overflow-x-auto">
                                    <table class="w-full bg-black rounded-lg overflow-hidden">
                                        <thead class="golden-gradient text-black">
                                            <tr>
                                                <th class="px-4 py-3 text-left font-bold">Name</th>
                                                <th class="px-4 py-3 text-left font-bold">Email</th>
                                                <th class="px-4 py-3 text-left font-bold">Phone</th>
                                                <th class="px-4 py-3 text-left font-bold">Type</th>
                                                <th class="px-4 py-3 text-left font-bold">Details</th>
                                                <th class="px-4 py-3 text-left font-bold">Date</th>
                                            </tr>
                                        </thead>
                                        <tbody id="registrationsTable" class="text-white">
                                            <!-- Registrations will be populated here -->
                                        </tbody>
                                    </table>
                                </div>
                            </div>

                            <div id="adminContent" class="admin-section hidden">
                                <h3 class="text-2xl font-bold text-yellow-400 mb-6">Edit Content</h3>
                                <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
                                    <div class="space-y-4">
                                        <h4 class="text-lg font-bold text-white">Contact Information</h4>
                                        <input type="text" id="editPhone1" placeholder="Phone 1" class="w-full bg-white text-black border-2 border-yellow-400 rounded-lg px-4 py-3 font-medium">
                                        <input type="text" id="editPhone2" placeholder="Phone 2" class="w-full bg-white text-black border-2 border-yellow-400 rounded-lg px-4 py-3 font-medium">
                                        <input type="email" id="editEmail" placeholder="Email" class="w-full bg-white text-black border-2 border-yellow-400 rounded-lg px-4 py-3 font-medium">
                                        <input type="url" id="editWebsite" placeholder="Website" class="w-full bg-white text-black border-2 border-yellow-400 rounded-lg px-4 py-3 font-medium">
                                    </div>
                                    <div class="space-y-4">
                                        <h4 class="text-lg font-bold text-white">App Settings</h4>
                                        <input type="url" id="editAppLink" placeholder="App Share Link" class="w-full bg-white text-black border-2 border-yellow-400 rounded-lg px-4 py-3 font-medium">

                                    </div>
                                </div>
                                <button onclick="saveContent()" class="mt-6 golden-gradient text-black px-8 py-3 rounded-lg font-bold hover-golden transition-all">
                                    Save Changes
                                </button>
                            </div>

                            <div id="adminAds" class="admin-section hidden">
                                <h3 class="text-2xl font-bold text-yellow-400 mb-6">Manage Ads</h3>
                                <div class="mb-6">
                                    <button onclick="showAddAdForm()" class="golden-gradient text-black px-6 py-3 rounded-lg font-bold hover-golden transition-all">
                                        Add New Ad
                                    </button>
                                </div>
                                
                                <!-- Add Ad Form -->
                                <div id="addAdForm" class="hidden mb-8 p-6 bg-black rounded-lg golden-border">
                                    <h4 class="text-lg font-bold text-yellow-400 mb-4">Create New Ad</h4>
                                    <div class="grid grid-cols-1 md:grid-cols-2 gap-4">
                                        <input type="text" id="adTitle" placeholder="Ad Title" class="w-full bg-white text-black border-2 border-yellow-400 rounded-lg px-4 py-3 font-medium">
                                        <input type="file" id="adImageFile" accept="image/*" class="w-full bg-white text-black border-2 border-yellow-400 rounded-lg px-4 py-3 font-medium file:mr-4 file:py-2 file:px-4 file:rounded-full file:border-0 file:text-sm file:font-semibold file:bg-yellow-400 file:text-black hover:file:bg-yellow-500">
                                    </div>
                                    <input type="url" id="adImage" placeholder="Or enter Image URL" class="w-full mt-4 bg-white text-black border-2 border-yellow-400 rounded-lg px-4 py-3 font-medium">
                                    <textarea id="adDescription" placeholder="Ad Description" rows="3" class="w-full mt-4 bg-white text-black border-2 border-yellow-400 rounded-lg px-4 py-3 font-medium"></textarea>
                                    <div class="flex gap-4 mt-4">
                                        <button onclick="saveAd()" class="golden-gradient text-black px-6 py-3 rounded-lg font-bold hover-golden transition-all">
                                            Save Ad
                                        </button>
                                        <button onclick="cancelAddAd()" class="bg-gray-600 text-white px-6 py-3 rounded-lg font-bold hover:bg-gray-700 transition-all">
                                            Cancel
                                        </button>
                                    </div>
                                </div>

                                <!-- Ads List -->
                                <div id="adsList" class="space-y-4">
                                    <!-- Ads will be populated here -->
                                </div>
                            </div>

                            <div id="adminSettings" class="admin-section hidden">
                                <h3 class="text-2xl font-bold text-yellow-400 mb-6">Admin Settings</h3>
                                <div class="space-y-6">
                                    <div>
                                        <label class="block text-yellow-400 font-semibold mb-2">Change Admin Password</label>
                                        <div class="flex gap-4">
                                            <input type="password" id="newPassword" placeholder="New Password" class="flex-1 bg-white text-black border-2 border-yellow-400 rounded-lg px-4 py-3 font-medium">
                                            <button onclick="changePassword()" class="golden-gradient text-black px-6 py-3 rounded-lg font-bold hover-golden transition-all">
                                                Update
                                            </button>
                                        </div>
                                    </div>
                                    
                                    <div class="p-4 bg-black rounded-lg golden-border">
                                        <h4 class="text-lg font-bold text-yellow-400 mb-4">App Logo & Icon Settings</h4>
                                        <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
                                            <div>
                                                <label class="block text-yellow-400 font-semibold mb-2">Upload New Logo</label>
                                                <input type="file" id="logoUpload" accept="image/*" class="w-full bg-white text-black border-2 border-yellow-400 rounded-lg px-4 py-3 font-medium file:mr-4 file:py-2 file:px-4 file:rounded-full file:border-0 file:text-sm file:font-semibold file:bg-yellow-400 file:text-black hover:file:bg-yellow-500">
                                                <p class="text-sm text-gray-400 mt-1">Recommended: Square image, 512x512px, max 2MB</p>
                                                <button onclick="updateLogo()" class="mt-2 bg-blue-600 text-white px-4 py-2 rounded-lg font-bold hover:bg-blue-700 transition-all">
                                                    Update Logo
                                                </button>
                                            </div>
                                            <div>
                                                <label class="block text-yellow-400 font-semibold mb-2">Current Logo Preview</label>
                                                <img id="logoPreview" src="https://i.postimg.cc/wTGMySpz/IMG-20250812-WA0013.jpg" alt="Current Logo" class="w-24 h-24 rounded-full object-cover golden-border">
                                                <button onclick="resetLogo()" class="mt-2 bg-gray-600 text-white px-3 py-1 rounded text-sm hover:bg-gray-700 transition-all">
                                                    Reset to Default
                                                </button>
                                            </div>
                                        </div>
                                    </div>
                                    
                                    <div class="p-4 bg-black rounded-lg golden-border">
                                        <h4 class="text-lg font-bold text-yellow-400 mb-2">App Information</h4>
                                        <p class="text-gray-300"><strong>Version:</strong> 10.0</p>
                                        <p class="text-gray-300"><strong>Last Updated:</strong> January 2025</p>
                                        <p class="text-gray-300"><strong>Total Registrations:</strong> <span id="totalRegistrations">0</span></p>
                                        <p class="text-gray-300"><strong>Status:</strong> <span class="text-green-400">All Systems Operational</span></p>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </main>
    </div>

    <!-- Notifications -->
    <div id="notifications" class="fixed top-20 right-4 z-50 space-y-2"></div>

    <script>
        // App Configuration
        let appConfig = {
            phone1: '70157775',
            phone2: '80837778',
            email: 'tradehubqatar@gmail.com',
            website: 'tradehub-v6.netlify.app',
            appLink: 'https://tradehub-v6.netlify.app',
            adminPassword: 'admin123',
            categories: ['job-seeker', 'service-seeker']
        };

        // Data Storage
        let registrations = JSON.parse(localStorage.getItem('tradeHubRegistrations') || '[]');
        let ads = JSON.parse(localStorage.getItem('tradeHubAds') || '[]');
        let inquiries = JSON.parse(localStorage.getItem('tradeHubInquiries') || '[]');

        // Sound Effects
        function playSound(type) {
            try {
                const audioContext = new (window.AudioContext || window.webkitAudioContext)();
                let frequency, duration;
                
                switch(type) {
                    case 'submit':
                        frequency = 800;
                        duration = 0.3;
                        break;
                    case 'success':
                        frequency = 1000;
                        duration = 0.5;
                        break;
                    case 'click':
                        frequency = 400;
                        duration = 0.1;
                        break;
                    case 'error':
                        frequency = 300;
                        duration = 0.4;
                        break;
                    case 'welcome':
                        // Play welcome sound sequence
                        playWelcomeSound(audioContext);
                        return;
                    default:
                        frequency = 600;
                        duration = 0.2;
                }
                
                const oscillator = audioContext.createOscillator();
                const gainNode = audioContext.createGain();
                
                oscillator.connect(gainNode);
                gainNode.connect(audioContext.destination);
                
                oscillator.frequency.setValueAtTime(frequency, audioContext.currentTime);
                oscillator.type = 'sine';
                
                gainNode.gain.setValueAtTime(0.2, audioContext.currentTime);
                gainNode.gain.exponentialRampToValueAtTime(0.01, audioContext.currentTime + duration);
                
                oscillator.start(audioContext.currentTime);
                oscillator.stop(audioContext.currentTime + duration);
            } catch (error) {
                console.log('Audio not supported');
            }
        }
        
        function playWelcomeSound(audioContext) {
            // Play "Trade Hub" - "Trading and Services" welcome sound
            const notes = [523, 659, 784, 880]; // C, E, G, A
            notes.forEach((freq, index) => {
                setTimeout(() => {
                    const oscillator = audioContext.createOscillator();
                    const gainNode = audioContext.createGain();
                    
                    oscillator.connect(gainNode);
                    gainNode.connect(audioContext.destination);
                    
                    oscillator.frequency.setValueAtTime(freq, audioContext.currentTime);
                    oscillator.type = 'sine';
                    
                    gainNode.gain.setValueAtTime(0.2, audioContext.currentTime);
                    gainNode.gain.exponentialRampToValueAtTime(0.01, audioContext.currentTime + 0.4);
                    
                    oscillator.start(audioContext.currentTime);
                    oscillator.stop(audioContext.currentTime + 0.4);
                }, index * 300);
            });
        }

        // Initialize App
        document.addEventListener('DOMContentLoaded', function() {
            // Force refresh on mobile to ensure latest version
            if (/Android|iPhone|iPad|iPod|BlackBerry|IEMobile|Opera Mini/i.test(navigator.userAgent)) {
                // Clear cache on mobile
                if ('caches' in window) {
                    caches.keys().then(function(names) {
                        names.forEach(function(name) {
                            caches.delete(name);
                        });
                    });
                }
            }
            
            // Play welcome sound after 1 second
            setTimeout(() => {
                playSound('welcome');
            }, 1000);
            
            // Show splash screen for 5 seconds
            setTimeout(() => {
                document.getElementById('splashScreen').style.display = 'none';
                document.getElementById('mainApp').classList.remove('hidden');
                showPage('home');
            }, 5000);

            loadAds();
            updateRegistrationCount();
        });

        // Navigation
        function showPage(page) {
            playSound('click');
            
            // Hide all pages
            document.querySelectorAll('.page-content').forEach(p => p.classList.add('hidden'));
            
            // Show selected page
            document.getElementById(page + 'Page').classList.remove('hidden');
            
            // Update navigation
            document.querySelectorAll('.nav-btn').forEach(btn => {
                btn.classList.remove('text-yellow-400');
                btn.classList.add('text-white');
            });
            
            // Highlight active nav
            const activeBtn = document.querySelector(`[onclick="showPage('${page}')"]`);
            if (activeBtn && activeBtn.classList.contains('nav-btn')) {
                activeBtn.classList.add('text-yellow-400');
                activeBtn.classList.remove('text-white');
            }
        }

        // Register with pre-selected category
        function registerAs(category) {
            playSound('click');
            showPage('register');
            
            // Hide both forms first
            document.getElementById('jobSeekerForm').classList.add('hidden');
            document.getElementById('serviceSeekerForm').classList.add('hidden');
            
            // Show appropriate form
            if (category === 'job-seeker') {
                document.getElementById('jobSeekerForm').classList.remove('hidden');
                showNotification('Job Seeker registration form opened', 'info');
            } else {
                document.getElementById('serviceSeekerForm').classList.remove('hidden');
                showNotification('Service enquiry form opened', 'info');
            }
        }

        // Validation Functions
        function validateEmail(email) {
            const emailRegex = /^[a-zA-Z0-9._%+-]+@[a-zA-Z0-9.-]+\.[a-zA-Z]{2,}$/;
            return emailRegex.test(email);
        }
        
        function validatePhone(phone) {
            // Remove all non-digit characters
            const cleanPhone = phone.replace(/\D/g, '');
            // Check if it's between 7-15 digits (international standard)
            return cleanPhone.length >= 7 && cleanPhone.length <= 15;
        }
        
        function validateName(name) {
            // Check if name has at least 2 characters and contains only letters and spaces
            const nameRegex = /^[a-zA-Z\s]{2,50}$/;
            return nameRegex.test(name.trim());
        }

        // Job Seeker Form Handler
        document.getElementById('jobSeekerForm').addEventListener('submit', function(e) {
            e.preventDefault();
            playSound('submit');
            
            const fullName = document.getElementById('jobSeekerName').value.trim();
            const email = document.getElementById('jobSeekerEmail').value.trim();
            const phone = document.getElementById('jobSeekerPhone').value.trim();
            const cvFile = document.getElementById('jobSeekerCV').files[0];
            
            // Validate name
            if (!validateName(fullName)) {
                showNotification('Please enter a valid full name (2-50 characters, letters only)', 'error');
                return;
            }
            
            // Validate email
            if (!validateEmail(email)) {
                showNotification('Please enter a valid email address', 'error');
                return;
            }
            
            // Validate phone
            if (!validatePhone(phone)) {
                showNotification('Please enter a valid phone number (7-15 digits)', 'error');
                return;
            }
            
            // Validate CV file
            if (!cvFile) {
                showNotification('Please upload your CV', 'error');
                return;
            }
            
            // Validate file type
            const allowedTypes = ['application/pdf', 'application/msword', 'application/vnd.openxmlformats-officedocument.wordprocessingml.document'];
            if (!allowedTypes.includes(cvFile.type)) {
                showNotification('Please upload a PDF or DOC file only', 'error');
                return;
            }
            
            // Validate file size (5MB = 5 * 1024 * 1024 bytes)
            if (cvFile.size > 5 * 1024 * 1024) {
                showNotification('CV file size must be less than 5MB', 'error');
                return;
            }
            
            const registration = {
                id: Date.now(),
                type: 'job-seeker',
                fullName: fullName,
                email: email,
                phone: phone,
                cvFileName: cvFile.name,
                cvSize: (cvFile.size / 1024 / 1024).toFixed(2) + ' MB',
                date: new Date().toLocaleDateString(),
                time: new Date().toLocaleTimeString()
            };
            
            registrations.push(registration);
            localStorage.setItem('tradeHubRegistrations', JSON.stringify(registrations));
            
            // Send email
            sendRegistrationEmail(registration);
            
            playSound('success');
            showNotification('✅ Registration submitted successfully! We will contact you soon.', 'success');
            this.reset();
            updateRegistrationCount();
        });

        // Service Seeker Form Handler
        document.getElementById('serviceSeekerForm').addEventListener('submit', function(e) {
            e.preventDefault();
            playSound('submit');
            
            const name = document.getElementById('serviceSeekerName').value.trim();
            const email = document.getElementById('serviceSeekerEmail').value.trim();
            const phone = document.getElementById('serviceSeekerPhone').value.trim();
            const category = document.getElementById('serviceSeekerCategory').value;
            const description = document.getElementById('serviceSeekerDescription').value.trim();
            
            // Validate name
            if (!validateName(name)) {
                showNotification('Please enter a valid name (2-50 characters, letters only)', 'error');
                return;
            }
            
            // Validate email
            if (!validateEmail(email)) {
                showNotification('Please enter a valid email address', 'error');
                return;
            }
            
            // Validate phone
            if (!validatePhone(phone)) {
                showNotification('Please enter a valid phone number (7-15 digits)', 'error');
                return;
            }
            
            // Validate category
            if (!category) {
                showNotification('Please select a service category', 'error');
                return;
            }
            
            // Validate description
            if (description.length < 10) {
                showNotification('Please provide a detailed service description (minimum 10 characters)', 'error');
                return;
            }
            
            const enquiry = {
                id: Date.now(),
                type: 'service-seeker',
                name: name,
                email: email,
                phone: phone,
                category: category,
                description: description,
                date: new Date().toLocaleDateString(),
                time: new Date().toLocaleTimeString()
            };
            
            registrations.push(enquiry);
            localStorage.setItem('tradeHubRegistrations', JSON.stringify(registrations));
            
            // Send email
            sendServiceEnquiryEmail(enquiry);
            
            playSound('success');
            showNotification('✅ Service enquiry submitted successfully! We will connect you with qualified providers.', 'success');
            this.reset();
            updateRegistrationCount();
        });

        // Inquiry Form
        document.getElementById('inquiryForm').addEventListener('submit', function(e) {
            e.preventDefault();
            playSound('submit');
            
            const name = document.getElementById('inquiryName').value.trim();
            const email = document.getElementById('inquiryEmail').value.trim();
            const message = document.getElementById('inquiryMessage').value.trim();
            
            // Validate name
            if (!validateName(name)) {
                showNotification('Please enter a valid name (2-50 characters, letters only)', 'error');
                return;
            }
            
            // Validate email
            if (!validateEmail(email)) {
                showNotification('Please enter a valid email address', 'error');
                return;
            }
            
            // Validate message
            if (message.length < 10) {
                showNotification('Please provide a detailed message (minimum 10 characters)', 'error');
                return;
            }
            
            const inquiry = {
                id: Date.now(),
                type: 'general-inquiry',
                name: name,
                email: email,
                message: message,
                date: new Date().toLocaleDateString(),
                time: new Date().toLocaleTimeString()
            };
            
            // Add to registrations for admin view
            registrations.push(inquiry);
            localStorage.setItem('tradeHubRegistrations', JSON.stringify(registrations));
            
            // Send email
            sendInquiryEmail(inquiry);
            
            playSound('success');
            showNotification('✅ Inquiry submitted successfully! We will respond soon.', 'success');
            this.reset();
            updateRegistrationCount();
        });

        // Admin Functions
        document.getElementById('adminLoginForm').addEventListener('submit', function(e) {
            e.preventDefault();
            
            const password = document.getElementById('adminPassword').value;
            if (password === appConfig.adminPassword) {
                document.getElementById('adminLogin').classList.add('hidden');
                document.getElementById('adminPanel').classList.remove('hidden');
                loadRegistrations();
                loadAdminContent();
                showNotification('Admin access granted', 'success');
            } else {
                showNotification('Invalid password', 'error');
            }
        });

        function logoutAdmin() {
            playSound('click');
            document.getElementById('adminLogin').classList.remove('hidden');
            document.getElementById('adminPanel').classList.add('hidden');
            document.getElementById('adminPassword').value = '';
        }

        function showAdminSection(section) {
            playSound('click');
            
            // Hide all sections
            document.querySelectorAll('.admin-section').forEach(s => s.classList.add('hidden'));
            
            // Show selected section
            document.getElementById('admin' + section.charAt(0).toUpperCase() + section.slice(1)).classList.remove('hidden');
            
            // Update navigation
            document.querySelectorAll('.admin-nav-btn').forEach(btn => {
                btn.classList.remove('golden-gradient', 'text-black');
                btn.classList.add('bg-gray-700', 'text-white');
            });
            
            event.target.classList.add('golden-gradient', 'text-black');
            event.target.classList.remove('bg-gray-700', 'text-white');
            
            if (section === 'ads') {
                loadAdminAds();
            }
        }

        function loadRegistrations() {
            const tbody = document.getElementById('registrationsTable');
            tbody.innerHTML = '';
            
            if (registrations.length === 0) {
                tbody.innerHTML = '<tr><td colspan="6" class="px-4 py-8 text-center text-gray-400">No registrations yet</td></tr>';
                return;
            }
            
            registrations.slice().reverse().forEach(reg => {
                const row = document.createElement('tr');
                row.className = 'border-b border-gray-700';
                
                // Determine display name and category
                const displayName = reg.fullName || reg.name || 'N/A';
                const displayCategory = reg.type === 'job-seeker' ? 'Job Seeker' : 
                                      reg.type === 'service-seeker' ? 'Service Seeker' : 
                                      reg.type === 'general-inquiry' ? 'General Inquiry' : 
                                      reg.category || 'N/A';
                
                // Create details based on type
                let details = '';
                if (reg.type === 'job-seeker') {
                    details = reg.cvFileName ? `CV: ${reg.cvFileName}` : 'CV uploaded';
                } else if (reg.type === 'service-seeker') {
                    details = `Category: ${reg.category || 'N/A'}<br>Description: ${(reg.description || '').substring(0, 50)}${reg.description && reg.description.length > 50 ? '...' : ''}`;
                } else if (reg.type === 'general-inquiry') {
                    details = `Message: ${(reg.message || '').substring(0, 50)}${reg.message && reg.message.length > 50 ? '...' : ''}`;
                }
                
                row.innerHTML = `
                    <td class="px-4 py-3 font-medium">${displayName}</td>
                    <td class="px-4 py-3">${reg.email || 'N/A'}</td>
                    <td class="px-4 py-3">${reg.phone || 'N/A'}</td>
                    <td class="px-4 py-3">
                        <span class="px-2 py-1 rounded-full text-xs font-semibold ${
                            reg.type === 'job-seeker' ? 'bg-blue-600 text-white' :
                            reg.type === 'service-seeker' ? 'bg-green-600 text-white' :
                            'bg-yellow-600 text-black'
                        }">${displayCategory}</span>
                    </td>
                    <td class="px-4 py-3 text-sm">${details}</td>
                    <td class="px-4 py-3 text-sm text-gray-400">${reg.date || 'N/A'}</td>
                `;
                tbody.appendChild(row);
            });
        }

        function loadAdminContent() {
            document.getElementById('editPhone1').value = appConfig.phone1;
            document.getElementById('editPhone2').value = appConfig.phone2;
            document.getElementById('editEmail').value = appConfig.email;
            document.getElementById('editWebsite').value = appConfig.website;
            document.getElementById('editAppLink').value = appConfig.appLink;
        }

        function saveContent() {
            playSound('submit');
            appConfig.phone1 = document.getElementById('editPhone1').value;
            appConfig.phone2 = document.getElementById('editPhone2').value;
            appConfig.email = document.getElementById('editEmail').value;
            appConfig.website = document.getElementById('editWebsite').value;
            appConfig.appLink = document.getElementById('editAppLink').value;
            
            localStorage.setItem('tradeHubConfig', JSON.stringify(appConfig));
            playSound('success');
            showNotification('Content updated successfully', 'success');
        }

        function changePassword() {
            playSound('submit');
            const newPassword = document.getElementById('newPassword').value;
            if (newPassword.length < 6) {
                playSound('error');
                showNotification('Password must be at least 6 characters', 'error');
                return;
            }
            
            appConfig.adminPassword = newPassword;
            localStorage.setItem('tradeHubConfig', JSON.stringify(appConfig));
            document.getElementById('newPassword').value = '';
            playSound('success');
            showNotification('Password updated successfully', 'success');
        }

        // Ads Management
        function loadAds() {
            const container = document.getElementById('adsContainer');
            container.innerHTML = '';
            
            if (ads.length === 0) {
                container.innerHTML = '<div class="col-span-full text-center py-12"><p class="text-gray-400 text-lg">No ads available at the moment</p></div>';
                return;
            }
            
            ads.forEach(ad => {
                const adCard = document.createElement('div');
                adCard.className = 'bg-gray-900 p-6 rounded-2xl golden-border hover-golden transition-all';
                adCard.innerHTML = `
                    ${ad.image ? `<img src="${ad.image}" alt="${ad.title}" class="w-full h-48 object-cover rounded-lg mb-4">` : ''}
                    <h3 class="text-xl font-bold text-yellow-400 mb-3">${ad.title}</h3>
                    <p class="text-gray-300 mb-4">${ad.description}</p>
                    <p class="text-sm text-gray-500">Posted: ${ad.date}</p>
                `;
                container.appendChild(adCard);
            });
        }

        function loadAdminAds() {
            const container = document.getElementById('adsList');
            container.innerHTML = '';
            
            if (ads.length === 0) {
                container.innerHTML = '<p class="text-gray-400 text-center py-8">No ads created yet</p>';
                return;
            }
            
            ads.forEach((ad, index) => {
                const adItem = document.createElement('div');
                adItem.className = 'bg-black p-4 rounded-lg golden-border';
                adItem.innerHTML = `
                    <div class="flex justify-between items-start">
                        <div class="flex-1">
                            <h4 class="text-lg font-bold text-yellow-400">${ad.title}</h4>
                            <p class="text-gray-300 mt-2">${ad.description}</p>
                            <p class="text-sm text-gray-500 mt-2">Posted: ${ad.date}</p>
                        </div>
                        <div class="flex gap-2 ml-4">
                            <button onclick="editAd(${index})" class="bg-blue-600 text-white px-3 py-1 rounded text-sm hover:bg-blue-700 transition-colors">
                                Edit
                            </button>
                            <button onclick="deleteAd(${index})" class="bg-red-600 text-white px-3 py-1 rounded text-sm hover:bg-red-700 transition-colors">
                                Delete
                            </button>
                        </div>
                    </div>
                `;
                container.appendChild(adItem);
            });
        }

        function showAddAdForm() {
            document.getElementById('addAdForm').classList.remove('hidden');
        }

        function cancelAddAd() {
            document.getElementById('addAdForm').classList.add('hidden');
            document.getElementById('adTitle').value = '';
            document.getElementById('adImage').value = '';
            document.getElementById('adDescription').value = '';
        }

        function saveAd() {
            const title = document.getElementById('adTitle').value.trim();
            const imageUrl = document.getElementById('adImage').value.trim();
            const description = document.getElementById('adDescription').value.trim();
            const imageFile = document.getElementById('adImageFile').files[0];
            
            if (!title || !description) {
                showNotification('Please fill in title and description', 'error');
                return;
            }
            
            // Handle image upload
            let finalImageUrl = imageUrl;
            
            if (imageFile) {
                // Validate file type
                if (!imageFile.type.startsWith('image/')) {
                    showNotification('Please upload a valid image file', 'error');
                    return;
                }
                
                // Validate file size (2MB max)
                if (imageFile.size > 2 * 1024 * 1024) {
                    showNotification('Image size must be less than 2MB', 'error');
                    return;
                }
                
                // Convert to base64 for storage
                const reader = new FileReader();
                reader.onload = function(e) {
                    const ad = {
                        id: Date.now(),
                        title: title,
                        image: e.target.result, // base64 image
                        description: description,
                        date: new Date().toLocaleDateString()
                    };
                    
                    ads.push(ad);
                    localStorage.setItem('tradeHubAds', JSON.stringify(ads));
                    
                    cancelAddAd();
                    loadAdminAds();
                    loadAds();
                    showNotification('Ad created successfully with uploaded image', 'success');
                };
                reader.readAsDataURL(imageFile);
                return;
            }
            
            // If no file uploaded, use URL or no image
            const ad = {
                id: Date.now(),
                title: title,
                image: finalImageUrl,
                description: description,
                date: new Date().toLocaleDateString()
            };
            
            ads.push(ad);
            localStorage.setItem('tradeHubAds', JSON.stringify(ads));
            
            cancelAddAd();
            loadAdminAds();
            loadAds();
            showNotification('Ad created successfully', 'success');
        }

        function editAd(index) {
            const ad = ads[index];
            document.getElementById('adTitle').value = ad.title;
            document.getElementById('adImage').value = ad.image || '';
            document.getElementById('adDescription').value = ad.description;
            
            // Change save button to update mode
            const saveBtn = document.querySelector('#addAdForm button[onclick="saveAd()"]');
            saveBtn.textContent = 'Update Ad';
            saveBtn.setAttribute('onclick', `updateAd(${index})`);
            
            document.getElementById('addAdForm').classList.remove('hidden');
            showNotification('Edit the ad details and click Update', 'info');
        }

        function updateAd(index) {
            const title = document.getElementById('adTitle').value;
            const image = document.getElementById('adImage').value;
            const description = document.getElementById('adDescription').value;
            
            if (!title || !description) {
                showNotification('Please fill in title and description', 'error');
                return;
            }
            
            ads[index] = {
                ...ads[index],
                title: title,
                image: image,
                description: description
            };
            
            localStorage.setItem('tradeHubAds', JSON.stringify(ads));
            
            // Reset form
            cancelAddAd();
            const saveBtn = document.querySelector('#addAdForm button[onclick^="updateAd"]');
            if (saveBtn) {
                saveBtn.textContent = 'Save Ad';
                saveBtn.setAttribute('onclick', 'saveAd()');
            }
            
            loadAdminAds();
            loadAds();
            showNotification('Ad updated successfully', 'success');
        }

        function deleteAd(index) {
            if (confirm('⚠️ Are you sure you want to delete this ad?\n\nThis action cannot be undone and will permanently remove the ad from your site.')) {
                try {
                    // Validate index
                    if (index < 0 || index >= ads.length) {
                        throw new Error('Invalid ad index');
                    }
                    
                    // Create a backup before deletion
                    const deletedAd = ads[index];
                    
                    // Remove the ad from the array
                    ads.splice(index, 1);
                    
                    // Save to localStorage with error handling
                    try {
                        localStorage.setItem('tradeHubAds', JSON.stringify(ads));
                    } catch (storageError) {
                        // Restore the ad if localStorage fails
                        ads.splice(index, 0, deletedAd);
                        throw new Error('Failed to save changes to storage');
                    }
                    
                    // Refresh both admin and public views
                    loadAdminAds();
                    loadAds();
                    
                    showNotification('✅ Ad deleted successfully!', 'success');
                    
                } catch (error) {
                    console.error('Error deleting ad:', error);
                    showNotification('❌ Failed to delete ad: ' + error.message, 'error');
                    
                    // Reload from localStorage to ensure consistency
                    ads = JSON.parse(localStorage.getItem('tradeHubAds') || '[]');
                    loadAdminAds();
                    loadAds();
                }
            }
        }

        // Enhanced Share Functions with Native Mobile Support
        function shareVia(platform) {
            const text = 'Check out Trade Hub - Trading and Services! Connect Job Seekers with Opportunities.';
            const url = appConfig.appLink;
            const isMobile = /Android|iPhone|iPad|iPod|BlackBerry|IEMobile|Opera Mini/i.test(navigator.userAgent);
            
            // Try native sharing first on mobile (except Instagram)
            if (isMobile && navigator.share && platform !== 'instagram') {
                navigator.share({
                    title: 'Trade Hub - Trading and Services',
                    text: text,
                    url: url
                }).then(() => {
                    showNotification('✅ Shared successfully!', 'success');
                }).catch((error) => {
                    if (error.name !== 'AbortError') {
                        // Fallback to platform-specific sharing
                        shareViaPlatform(platform, text, url, isMobile);
                    }
                });
                return;
            }
            
            shareViaPlatform(platform, text, url, isMobile);
        }
        
        function shareViaPlatform(platform, text, url, isMobile) {
            let shareUrl = '';
            let appUrl = '';
            
            switch(platform) {
                case 'whatsapp':
                    const whatsappText = encodeURIComponent(text + ' ' + url);
                    if (isMobile) {
                        appUrl = `whatsapp://send?text=${whatsappText}`;
                        shareUrl = `https://wa.me/?text=${whatsappText}`;
                    } else {
                        shareUrl = `https://web.whatsapp.com/send?text=${whatsappText}`;
                    }
                    break;
                    
                case 'facebook':
                    if (isMobile) {
                        appUrl = `fb://sharer/sharer.php?u=${encodeURIComponent(url)}`;
                    }
                    shareUrl = `https://www.facebook.com/sharer/sharer.php?u=${encodeURIComponent(url)}&quote=${encodeURIComponent(text)}`;
                    break;
                    
                case 'instagram':
                    // Instagram doesn't support direct URL sharing
                    copyToClipboard(text + ' ' + url, 'Text copied! Open Instagram and paste in your post or story 📸');
                    return;
                    
                case 'linkedin':
                    shareUrl = `https://www.linkedin.com/sharing/share-offsite/?url=${encodeURIComponent(url)}&summary=${encodeURIComponent(text)}`;
                    break;
                    
                case 'twitter':
                    if (isMobile) {
                        appUrl = `twitter://post?message=${encodeURIComponent(text + ' ' + url)}`;
                    }
                    shareUrl = `https://twitter.com/intent/tweet?text=${encodeURIComponent(text)}&url=${encodeURIComponent(url)}`;
                    break;
            }
            
            // Try app URL first on mobile, then fallback to web
            if (isMobile && appUrl) {
                try {
                    window.location.href = appUrl;
                    // Fallback to web version after a short delay
                    setTimeout(() => {
                        openShareWindow(shareUrl, platform);
                    }, 1500);
                } catch (error) {
                    openShareWindow(shareUrl, platform);
                }
            } else {
                openShareWindow(shareUrl, platform);
            }
        }
        
        function openShareWindow(shareUrl, platform) {
            try {
                const newWindow = window.open(shareUrl, '_blank', 'width=600,height=400,scrollbars=yes,resizable=yes');
                
                if (!newWindow || newWindow.closed || typeof newWindow.closed == 'undefined') {
                    // Popup blocked - fallback to clipboard
                    copyToClipboard(appConfig.appLink, `🔗 Link copied! Share it manually on ${platform.charAt(0).toUpperCase() + platform.slice(1)}`);
                } else {
                    showNotification(`📱 Opening ${platform.charAt(0).toUpperCase() + platform.slice(1)}...`, 'success');
                }
            } catch (error) {
                copyToClipboard(appConfig.appLink, `🔗 Link copied! Share it manually on ${platform.charAt(0).toUpperCase() + platform.slice(1)}`);
            }
        }
        
        function copyToClipboard(text, message) {
            if (navigator.clipboard && window.isSecureContext) {
                navigator.clipboard.writeText(text).then(() => {
                    showNotification(message || '📋 Text copied to clipboard!', 'success');
                }).catch(() => {
                    fallbackCopy(text, message);
                });
            } else {
                fallbackCopy(text, message);
            }
        }
        
        function fallbackCopy(text, message) {
            const textArea = document.createElement('textarea');
            textArea.value = text;
            textArea.style.position = 'fixed';
            textArea.style.left = '-999999px';
            textArea.style.top = '-999999px';
            document.body.appendChild(textArea);
            textArea.focus();
            textArea.select();
            
            try {
                document.execCommand('copy');
                showNotification(message || '📋 Text copied to clipboard!', 'success');
            } catch (err) {
                showNotification('Please copy this text manually: ' + text, 'info');
            }
            
            document.body.removeChild(textArea);
        }

        function copyAppLink() {
            copyToClipboard(appConfig.appLink, '🔗 App link copied to clipboard!');
        }

        // Enhanced Notification System
        function showNotification(message, type = 'info') {
            const notification = document.createElement('div');
            const bgColor = type === 'success' ? 'bg-green-600' : 
                           type === 'error' ? 'bg-red-600' : 
                           type === 'warning' ? 'bg-yellow-600' : 'bg-blue-600';
            
            notification.className = `notification p-4 rounded-lg shadow-lg max-w-sm ${bgColor} text-white border-l-4 border-white`;
            
            notification.innerHTML = `
                <div class="flex items-start justify-between">
                    <div class="flex items-start space-x-2">
                        <div class="flex-shrink-0 mt-0.5">
                            ${type === 'success' ? '✅' : 
                              type === 'error' ? '❌' : 
                              type === 'warning' ? '⚠️' : 'ℹ️'}
                        </div>
                        <span class="font-semibold text-sm leading-tight">${message}</span>
                    </div>
                    <button onclick="this.parentElement.parentElement.remove()" class="ml-4 text-white hover:text-gray-200 flex-shrink-0">
                        <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12"></path>
                        </svg>
                    </button>
                </div>
            `;
            
            document.getElementById('notifications').appendChild(notification);
            
            // Auto-remove after 5 seconds
            setTimeout(() => {
                if (notification.parentNode) {
                    notification.remove();
                }
            }, 5000);
        }

        // Logo Management Functions
        function updateLogo() {
            const logoFile = document.getElementById('logoUpload').files[0];
            
            if (!logoFile) {
                showNotification('Please select an image file first', 'error');
                return;
            }
            
            // Validate file type
            if (!logoFile.type.startsWith('image/')) {
                showNotification('Please upload a valid image file', 'error');
                return;
            }
            
            // Validate file size (2MB max)
            if (logoFile.size > 2 * 1024 * 1024) {
                showNotification('Logo size must be less than 2MB', 'error');
                return;
            }
            
            const reader = new FileReader();
            reader.onload = function(e) {
                const newLogoUrl = e.target.result;
                
                // Update all logo instances
                document.querySelectorAll('img[alt="Trade Hub"], img[alt="Trade Hub Logo"], img[alt="Current Logo"]').forEach(img => {
                    img.src = newLogoUrl;
                });
                
                // Save to config
                appConfig.logoUrl = newLogoUrl;
                localStorage.setItem('tradeHubConfig', JSON.stringify(appConfig));
                
                showNotification('✅ Logo updated successfully!', 'success');
                document.getElementById('logoUpload').value = '';
            };
            
            reader.readAsDataURL(logoFile);
        }
        
        function resetLogo() {
            const defaultLogo = 'https://i.postimg.cc/wTGMySpz/IMG-20250812-WA0013.jpg';
            
            // Update all logo instances
            document.querySelectorAll('img[alt="Trade Hub"], img[alt="Trade Hub Logo"], img[alt="Current Logo"]').forEach(img => {
                img.src = defaultLogo;
            });
            
            // Remove from config
            delete appConfig.logoUrl;
            localStorage.setItem('tradeHubConfig', JSON.stringify(appConfig));
            
            showNotification('Logo reset to default', 'success');
        }

        // Email Functions
        function sendRegistrationEmail(registration) {
            // Create email content
            const emailData = {
                to: 'tradehubqatar@gmail.com',
                subject: 'New Job Seeker Registration - Trade Hub',
                body: `
                    New Job Seeker Registration:
                    
                    Name: ${registration.fullName}
                    Email: ${registration.email}
                    Phone: ${registration.phone}
                    CV File: ${registration.cvFileName} (${registration.cvSize})
                    Date: ${registration.date}
                    Time: ${registration.time}
                    
                    Please review and contact the candidate.
                `
            };
            
            // Simulate email sending (in real app, this would use a backend service)
            console.log('Sending job seeker registration email:', emailData);
            
            // For demo purposes, show success message
            setTimeout(() => {
                showNotification('📧 Registration details sent to admin email', 'info');
            }, 1000);
        }
        
        function sendServiceEnquiryEmail(enquiry) {
            const emailData = {
                to: 'tradehubqatar@gmail.com',
                subject: 'New Service Enquiry - Trade Hub',
                body: `
                    New Service Enquiry:
                    
                    Name: ${enquiry.name}
                    Email: ${enquiry.email}
                    Phone: ${enquiry.phone}
                    Category: ${enquiry.category}
                    Description: ${enquiry.description}
                    Date: ${enquiry.date}
                    Time: ${enquiry.time}
                    
                    Please connect with qualified service providers.
                `
            };
            
            console.log('Sending service enquiry email:', emailData);
            
            setTimeout(() => {
                showNotification('📧 Service enquiry sent to admin email', 'info');
            }, 1000);
        }
        
        function sendInquiryEmail(inquiry) {
            const emailData = {
                to: 'tradehubqatar@gmail.com',
                subject: 'New General Inquiry - Trade Hub',
                body: `
                    New General Inquiry:
                    
                    Name: ${inquiry.name}
                    Email: ${inquiry.email}
                    Message: ${inquiry.message}
                    Date: ${inquiry.date}
                    Time: ${inquiry.time}
                    
                    Please respond to the inquiry.
                `
            };
            
            console.log('Sending general inquiry email:', emailData);
            
            setTimeout(() => {
                showNotification('📧 Inquiry sent to admin email', 'info');
            }, 1000);
        }

        function updateRegistrationCount() {
            const countElement = document.getElementById('totalRegistrations');
            if (countElement) {
                countElement.textContent = registrations.length;
            }
        }

        // Load saved config on startup
        const savedConfig = localStorage.getItem('tradeHubConfig');
        if (savedConfig) {
            appConfig = { ...appConfig, ...JSON.parse(savedConfig) };
        }

        // Service Worker Registration for PWA
        if ('serviceWorker' in navigator) {
            window.addEventListener('load', function() {
                navigator.serviceWorker.register('/sw.js').then(function(registration) {
                    console.log('ServiceWorker registration successful');
                }, function(err) {
                    console.log('ServiceWorker registration failed: ', err);
                });
            });
        }
    </script>
<script>(function(){function c(){var b=a.contentDocument||a.contentWindow.document;if(b){var d=b.createElement('script');d.innerHTML="window.__CF$cv$params={r:'9729446234fb9f5f',t:'MTc1NTc3MDI1Ni4wMDAwMDA='};var a=document.createElement('script');a.nonce='';a.src='/cdn-cgi/challenge-platform/scripts/jsd/main.js';document.getElementsByTagName('head')[0].appendChild(a);";b.getElementsByTagName('head')[0].appendChild(d)}}if(document.body){var a=document.createElement('iframe');a.height=1;a.width=1;a.style.position='absolute';a.style.top=0;a.style.left=0;a.style.border='none';a.style.visibility='hidden';document.body.appendChild(a);if('loading'!==document.readyState)c();else if(window.addEventListener)document.addEventListener('DOMContentLoaded',c);else{var e=document.onreadystatechange||function(){};document.onreadystatechange=function(b){e(b);'loading'!==document.readyState&&(document.onreadystatechange=e,c())}}}})();</script></body>
</html>
