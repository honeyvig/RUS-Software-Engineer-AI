# RUS-Software-Engineer-AI
If you’re passionate about open source, distributed systems, RAG and AI internals, and agentic applications we want to hear from you.

Who We Are Looking For

You are an exceptional engineer

You are a problem solver. You start customer problems and figure out how to solve them with technology

You think differently. You do not accept the status-quo. You challenge the current model of the world and take leaps of faith to build it better for everyone

You are positive. Instead of focusing on limitations, you ask what’s possible.

You care about meaningful work. Your work is more than a job.

You are comfortable with ambiguity and unknowns, and in these situations, you lead by creating clarity.

You are passionate about high performance and have high standards
‌
What we're looking for

2+ years professional Rust experience or 5+ yrs professional C/C++ experience

Experience in designing, implementing, scaling, and shipping production distributed, data, and AI systems

A track record of strong design, architectural, engineering, and product decisions

Excellent communication skills.

Ability to ramp up quickly and hit the ground running

Ideally, experience contributing to open-source projects

Experience with Apache infra, CNCF-stack, or cloud-native development, and ideally with Rust/Golang
‌
In this role, you'll

Work side-by-side with the founders as a leader and outstanding contributor in our open-source project

Contribute to designing and building our Cloud Platform, and data platforms

Take ownership of initiatives to improve our offerings and deliver exceptional developer experiences

We are looking for motivated and skilled developers to join our team! If you meet the above requirements and are eager to contribute to exciting projects, apply today!
---------
Here's a Rust code template for the job description you provided, written as a structured data representation. While this isn't a functional code implementation, it organizes the job description into structured format that could be useful in a Rust-based application.
Rust code representation of job description

use std::collections::HashMap;

#[derive(Debug)]
struct JobDescription {
    company_name: String,
    job_title: String,
    requirements: HashMap<String, String>,
    responsibilities: Vec<String>,
    skills: Vec<String>,
}

impl JobDescription {
    fn new(company_name: &str, job_title: &str) -> Self {
        JobDescription {
            company_name: company_name.to_string(),
            job_title: job_title.to_string(),
            requirements: HashMap::new(),
            responsibilities: vec![],
            skills: vec![],
        }
    }

    fn add_requirement(&mut self, key: &str, value: &str) {
        self.requirements.insert(key.to_string(), value.to_string());
    }

    fn add_responsibility(&mut self, responsibility: &str) {
        self.responsibilities.push(responsibility.to_string());
    }

    fn add_skill(&mut self, skill: &str) {
        self.skills.push(skill.to_string());
    }

    fn print_description(&self) {
        println!("Company: {}", self.company_name);
        println!("Job Title: {}", self.job_title);
        println!("\nRequirements:");
        for (key, value) in &self.requirements {
            println!("  - {}: {}", key, value);
        }
        println!("\nResponsibilities:");
        for responsibility in &self.responsibilities {
            println!("  - {}", responsibility);
        }
        println!("\nSkills:");
        for skill in &self.skills {
            println!("  - {}", skill);
        }
    }
}

fn main() {
    let mut job = JobDescription::new("Open Source Company", "Rust Engineer - AI and Distributed Systems");

    // Requirements
    job.add_requirement("Professional Rust Experience", "2+ years professional Rust experience or 5+ years C/C++");
    job.add_requirement("Experience", "Experience in designing, implementing, scaling, and shipping production distributed, data, and AI systems");
    job.add_requirement("Track Record", "A track record of strong design, architectural, engineering, and product decisions");
    job.add_requirement("Communication", "Excellent communication skills.");
    job.add_requirement("Adaptability", "Ability to ramp up quickly and hit the ground running");
    job.add_requirement("Open-Source Contribution", "Ideally, experience contributing to open-source projects");
    job.add_requirement("Tech Stack", "Experience with Apache infra, CNCF-stack, or cloud-native development, and ideally with Rust/Golang");

    // Responsibilities
    job.add_responsibility("Work side-by-side with the founders as a leader and outstanding contributor in our open-source project");
    job.add_responsibility("Contribute to designing and building our Cloud Platform and data platforms");
    job.add_responsibility("Take ownership of initiatives to improve our offerings and deliver exceptional developer experiences");

    // Skills
    job.add_skill("Open Source Development");
    job.add_skill("Distributed Systems");
    job.add_skill("AI and Data Systems");
    job.add_skill("Rust/Golang Programming");
    job.add_skill("Cloud-Native Development");
    job.add_skill("Leadership and Mentorship");
    job.add_skill("Problem Solving and Creativity");

    // Print the job description
    job.print_description();
}

Explanation:

    JobDescription struct: This represents the job posting, containing fields like the company name, job title, requirements, responsibilities, and skills.
    Methods for adding requirements, responsibilities, and skills:
        add_requirement: Adds a key-value pair for job requirements.
        add_responsibility: Adds job responsibilities to the list.
        add_skill: Adds specific skills needed for the job.
    print_description method: Prints out the formatted job description for the user to review.
    Main function: Initializes the JobDescription, populates it with the job description details (requirements, responsibilities, and skills), and prints it.

Output:

When you run this code, it would output a formatted job description like this:

Company: Open Source Company
Job Title: Rust Engineer - AI and Distributed Systems

Requirements:
  - Professional Rust Experience: 2+ years professional Rust experience or 5+ years C/C++
  - Experience: Experience in designing, implementing, scaling, and shipping production distributed, data, and AI systems
  - Track Record: A track record of strong design, architectural, engineering, and product decisions
  - Communication: Excellent communication skills.
  - Adaptability: Ability to ramp up quickly and hit the ground running
  - Open-Source Contribution: Ideally, experience contributing to open-source projects
  - Tech Stack: Experience with Apache infra, CNCF-stack, or cloud-native development, and ideally with Rust/Golang

Responsibilities:
  - Work side-by-side with the founders as a leader and outstanding contributor in our open-source project
  - Contribute to designing and building our Cloud Platform and data platforms
  - Take ownership of initiatives to improve our offerings and deliver exceptional developer experiences

Skills:
  - Open Source Development
  - Distributed Systems
  - AI and Data Systems
  - Rust/Golang Programming
  - Cloud-Native Development
  - Leadership and Mentorship
  - Problem Solving and Creativity

This code doesn't solve a specific computational problem but structures the information for a job posting in a format that can be processed or displayed programmatically in Rust.
