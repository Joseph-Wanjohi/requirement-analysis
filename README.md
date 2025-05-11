<!-- README: Requirement Analysis in Software Development -->

<section id="what-is-requirement-analysis">
  <h2>What is Requirement Analysis?</h2>
  <p>
    Requirement Analysis is the process of identifying, documenting, and managing the needs and constraints of stakeholders so that the resulting software solution meets their expectations and business goals. It kicks off the SDLC by translating stakeholder inputs into clear, actionable specifications and helps avoid costly rework later in development.
  </p>
</section>

<section id="why-important">
  <h2>Why is Requirement Analysis Important?</h2>
  <ul>
    <li>
      <strong>Aligns Stakeholder Expectations</strong><br>
      Ensures all parties—clients, users, developers—agree on what the software must do, reducing ambiguity and disputes.
    </li>
    <li>
      <strong>Guides Project Scope &amp; Planning</strong><br>
      Provides a firm foundation for estimating effort, scheduling tasks, and allocating resources, preventing scope creep.
    </li>
    <li>
      <strong>Improves Quality &amp; Testability</strong><br>
      Well-defined requirements yield measurable, testable acceptance criteria and reduce defects in later phases.
    </li>
  </ul>
</section>

<section id="key-activities">
  <h2>Key Activities in Requirement Analysis</h2>
  <ul>
    <li>
      <strong>Requirement Gathering:</strong> Collect raw needs from users, clients, and stakeholders through interviews, surveys, and document reviews.
    </li>
    <li>
      <strong>Requirement Elicitation:</strong> Use techniques like workshops, prototyping, and user stories to draw out hidden or implied needs.
    </li>
    <li>
      <strong>Requirement Documentation:</strong> Record requirements clearly—using SRS documents, user stories, or use cases—so they can be reviewed and approved.
    </li>
    <li>
      <strong>Requirement Analysis &amp; Modeling:</strong> Organize and refine requirements, model workflows (e.g., UML diagrams), and resolve conflicts or redundancies.
    </li>
    <li>
      <strong>Requirement Validation:</strong> Confirm with stakeholders that the documented requirements accurately reflect their needs and are feasible to implement.
    </li>
  </ul>
</section>

<section id="types-of-requirements">
  <h2>Types of Requirements</h2>

  <h3>Functional Requirements</h3>
  <p>Define specific behaviors or functions the system must perform.</p>
  <ul>
    <li><strong>Search &amp; Booking:</strong> The system shall allow users to search for available rooms by date, location, and price.</li>
    <li><strong>Payment Processing:</strong> The system shall process credit-card and mobile-money payments during checkout.</li>
  </ul>

  <h3>Non-functional Requirements</h3>
  <p>Set quality attributes and constraints on system performance.</p>
  <ul>
    <li><strong>Performance:</strong> Search results must load within 2 seconds under peak load.</li>
    <li><strong>Security:</strong> User credentials and payment data must be encrypted at rest and in transit.</li>
    <li><strong>Usability:</strong> The booking flow shall require no more than five clicks from search to confirmation.</li>
  </ul>
</section>

<section id="use-case-diagrams">
  <h2>Use Case Diagrams</h2>
  <p>
    Use Case Diagrams are UML models that illustrate how “actors” (users or external systems) interact with the software to achieve goals. They provide a high-level, visual overview of system scope, improve communication with non-technical stakeholders, and serve as a foundation for detailed design.
  </p>
  <p>
    <img src="use-case.drawio.svg" alt="Booking System Use Case Diagram" />
  </p>
  <h3>Primary Actors &amp; Use Cases</h3>
  <ul>
    <li><strong>Guest:</strong> Search Hotels, Make Booking, Cancel Booking</li>
    <li><strong>Hotel Manager:</strong> Manage Listings, View Bookings</li>
    <li><strong>Payment Gateway:</strong> Process Payment</li>
  </ul>
</section>

<section id="acceptance-criteria">
  <h2>Acceptance Criteria</h2>
  <p>
    Acceptance Criteria are explicit, pass/fail conditions that a feature must meet before it’s considered “done.” They align development and QA around clear definitions of success, reducing misunderstandings.
  </p>
  <h3>Example (Checkout Feature)</h3>
  <ul>
    <li>Given a user selects a room and proceeds to checkout</li>
    <li>When they enter valid payment details and confirm</li>
    <li>Then the system processes the payment and displays a confirmation message</li>
    <li>And an email receipt is sent to the user’s registered address</li>
  </ul>
</section>
