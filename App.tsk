import React from 'react';
import { Briefcase, GraduationCap, MapPin, Mail, Phone, Award, Code, PenTool as Tool } from 'lucide-react';

function App() {
  return (
    <div className="min-h-screen bg-gray-100 p-8">
      <div className="max-w-4xl mx-auto space-y-6">
        {/* Header/Intro Section */}
        <div className="bg-white rounded-lg shadow-md p-6">
          <div className="flex items-start gap-6">
            <img 
              src="https://images.unsplash.com/photo-1633332755192-727a05c4013d?w=400&h=400&fit=crop"
              alt="Profile"
              className="w-32 h-32 rounded-full object-cover"
            />
            <div className="flex-1">
              <h1 className="text-2xl font-bold">Nava Bhargav Gedda</h1>
              <p className="text-lg text-gray-600 mt-1">
                Graduate Student & Software Engineer with expertise in Analytics and Machine Learning
              </p>
              <div className="flex items-center gap-2 mt-2 text-gray-600">
                <MapPin size={16} />
                <span>London, United Kingdom</span>
              </div>
              <div className="flex items-center gap-4 mt-2 text-gray-600">
                <div className="flex items-center gap-2">
                  <Mail size={16} />
                  <span>navabhargavg@gmail.com</span>
                </div>
                <div className="flex items-center gap-2">
                  <Phone size={16} />
                  <span>07741944719</span>
                </div>
              </div>
            </div>
          </div>
          
          <div className="mt-4">
            <p className="text-gray-700">
              Analytics professional with 2.6 years of experience specializing in predictive modeling, 
              process improvement, and software development. MSc Business Analytics graduate combining 
              technical expertise with business acumen to deliver data-driven solutions.
            </p>
          </div>
        </div>

        {/* Experience Section */}
        <div className="bg-white rounded-lg shadow-md p-6">
          <div className="flex items-center gap-2 mb-4">
            <Briefcase className="text-blue-600" />
            <h2 className="text-xl font-bold">Experience</h2>
          </div>

          <div className="space-y-6">
            <div>
              <h3 className="font-semibold">Student Consultant & Venture Capitalist</h3>
              <p className="text-gray-600">QMUL • Full-time</p>
              <p className="text-gray-600">Sep 2023 - Sep 2024 • 1 year</p>
              <p className="mt-2">
                • Delivered strategic insights improving student union operations with 15% increased engagement<br/>
                • Collaborated with 25 VCs to evaluate and fund 10+ student-led startups
              </p>
            </div>

            <div>
              <h3 className="font-semibold">Software Engineer II</h3>
              <p className="text-gray-600">HCLTech • Full-time</p>
              <p className="text-gray-600">Oct 2020 - May 2023 • 2 years 8 months</p>
              <p className="mt-2">
                • Led Python-based software solutions development, reducing data processing timeouts by 20%<br/>
                • Automated workflows for Sony Android devices, reducing manual processing time by 30%<br/>
                • Developed 25+ custom Python scripts using NumPy, Pandas, and Flask<br/>
                • Created 5+ interactive dashboards using Python and Tableau<br/>
                • Led Agile teams and improved team efficiency by 20%<br/>
                • Automated Syncada portal invoice retrieval, saving 10+ hours weekly
              </p>
            </div>
          </div>
        </div>

        {/* Education Section */}
        <div className="bg-white rounded-lg shadow-md p-6">
          <div className="flex items-center gap-2 mb-4">
            <GraduationCap className="text-blue-600" />
            <h2 className="text-xl font-bold">Education</h2>
          </div>

          <div className="space-y-4">
            <div>
              <h3 className="font-semibold">Queen Mary University of London</h3>
              <p className="text-gray-600">MSc Business Analytics • Distinction</p>
              <p className="text-gray-600">2023 - 2024</p>
            </div>

            <div>
              <h3 className="font-semibold">Jawaharlal Nehru Technological University, Kakinada</h3>
              <p className="text-gray-600">BTech in Electrical and Electronics Engineering • CGPA: 8.32</p>
              <p className="text-gray-600">2016 - 2020</p>
            </div>
          </div>
        </div>

        {/* Projects Section */}
        <div className="bg-white rounded-lg shadow-md p-6">
          <div className="flex items-center gap-2 mb-4">
            <Code className="text-blue-600" />
            <h2 className="text-xl font-bold">Featured Projects</h2>
          </div>

          <div className="space-y-4">
            <div>
              <h3 className="font-semibold">Predictive Analysis of Airbnb Listing Prices in New York City</h3>
              <p className="text-gray-600">Jan 2024</p>
              <p className="mt-2">
                Developed ML pipeline analyzing 50,000+ listings, improving forecasting accuracy by 15% using 
                feature engineering and PCA optimization.
              </p>
            </div>

            <div>
              <h3 className="font-semibold">Bloomberg Financial Analytics Visual Dashboard</h3>
              <p className="text-gray-600">Aug 2024</p>
              <p className="mt-2">
                Built stock prediction models and Bloomberg-driven dashboard, enhancing forecasting accuracy by 20%.
              </p>
            </div>
          </div>
        </div>

        {/* Skills & Certifications Section */}
        <div className="bg-white rounded-lg shadow-md p-6">
          <div className="flex items-center gap-2 mb-4">
            <Tool className="text-blue-600" />
            <h2 className="text-xl font-bold">Skills & Certifications</h2>
          </div>

          <div className="space-y-4">
            <div>
              <h3 className="font-semibold">Certifications</h3>
              <p className="mt-1">AWS Cloud Practitioner • Bloomberg ESG • BFF & BMC certification</p>
            </div>

            <div>
              <h3 className="font-semibold">Technical Skills</h3>
              <div className="flex flex-wrap gap-2 mt-2">
                {['Python', 'SQL', 'R', 'PostgreSQL', 'C++', 'HTML/CSS', 'JavaScript', 'Git', 
                  'Kubernetes', 'Tableau', 'Power BI', 'Docker', 'Fast API', 'Machine Learning',
                  'Data Analytics', 'Business Intelligence'].map((skill) => (
                  <span key={skill} className="bg-blue-100 text-blue-800 px-3 py-1 rounded-full text-sm">
                    {skill}
                  </span>
                ))}
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  );
}

export default App;
