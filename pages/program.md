---
# permalink: /about/
layout: single
title: "Program"
header:
    image: /assets/images/teaser/gd2026/homepage-teaser.png
    caption: "Image credit: [**Organizer**](https://brocku.ca/)"
# last_modified_at: 2025-11-26
toc: true
---

<style type="text/css">
  table {
    width: 100%;
    display: table;
    table-layout: fixed;
  }
thead.day-header {
  position: sticky;
  top: 0px;
  font-size: 1em; 
  font-weight: bold;
  text-align: center;
  padding: 8px;
  background-color: #f5f5f5;
}
  th { text-align: center; }
  tbody > tr:hover { background-color: #dadada; }

  span.title { font-weight: 500; }
  td > p { font-size: 1em !important; }
  td > p:last-of-type { margin-bottom: 0 !important; }
  .MathJax_Display { display: inherit !important; }

  tbody > tr.phd-school {
    background-color: #f3e3df;
    color: #2C2C2C;
  }
  
  tbody > tr.phd-school.header {
    background-color:#A34D3A;
    color: #fff;
  }
  
  tbody > tr.phd-school.header a {
    color: #fff !important;
  }
  
  tbody > tr.phd-school:hover {
    background-color: #f8e8e4;
  }
  
  tbody > tr.phd-school.header:hover {
    background-color: #b55a47;
  }

  tbody > tr.registration,
  tbody > tr.reception{
    background-color:#FFE9AB;
    color: #2C2C2C;
  }

  tbody > tr.coffee,
  tbody > tr.lunch,
  span.coffee {
    background-color:#FFFFD5;
    color: #2C2C2C;
  }
  
  tbody > tr.registration:hover,
  tbody > tr.reception:hover,
  tbody > tr.coffee:hover,
  tbody > tr.lunch:hover {
    background-color: #fff0c0;
  }

  tbody > tr a {
    color: #2C2C2C !important;
  }
  
  .Location-info {
    font-style: italic;
  }

  tbody > tr.session {
    background-color: #dab3aa;
  }
  
  tbody > tr.session:hover {
    background-color: #e0b9b0;
  }
  
  tbody > tr.session.light {
    background-color: #f3e3df;
  }
  
  tbody > tr.session.light:hover {
    background-color: #f8e8e4;
  }
  
  tbody > tr.session.header {
    background-color: #843F30;
    color: #fff;
  }
  
  tbody > tr.session.header:hover {
    background-color: #954a3a;
  }

  tbody > tr.poster,
  tbody > tr.invited-talk {
    background-color: rgb(162, 229, 248);
  }
  
  tbody > tr.poster:hover,
  tbody > tr.invited-talk:hover {
    background-color: rgb(172, 239, 255);
  }
  
  tbody > tr.poster.header,
  tbody > tr.invited-talk.header {
    background-color:#42B5D5;
  }
  
  tbody > tr.poster.header:hover,
  tbody > tr.invited-talk.header:hover {
    background-color: #4cc0e0;
  }

  tbody > tr.gdc,
  tbody > tr.business-meeting,
  tbody > tr.special {
    background-color: #42B5D5;
  }
  
  tbody > tr.gdc:hover,
  tbody > tr.business-meeting:hover,
  tbody > tr.special:hover {
    background-color: #4cc0e0;
  }

  ul.poster-list {
    margin-inline-start: 0;
    padding-inline-start: 0;
    list-style-position: inside;
    list-style-type: none;
  }
  ul.poster-list > li { font-size: inherit !important; }
  span.speaker { text-decoration: underline; }
  
  /* Collapsible session styles - Only show triangles for collapsible rows */
  /* Target ALL possible header types */
  tr.session.header, tr.poster.header, tr.phd-school.header, tr.gdc {
    cursor: pointer;
    position: relative;
  }
  
  /* Show triangles ONLY for rows with collapsible class */
  /* Use ONLY the cell approach for better Safari compatibility */
  tr.collapsible td:last-child {
    position: relative;
  }
  
  tr.collapsible td:last-child::after {
    content: '▼';
    position: absolute;
    right: 10px;
    top: 50%;
    transform: translateY(-50%);
    transition: transform 0.3s ease;
    font-size: 12px;
    color: inherit;
    z-index: 10;
    pointer-events: none;
  }
  
  tr.collapsible.collapsed td:last-child::after {
    transform: translateY(-50%) rotate(-90deg);
  }
  
  .session-content {
    transition: all 0.3s ease;
  }
  
  .session-content.collapsed {
    display: none;
  }
  
  /* Additional mobile and Safari compatibility fixes */
  @media (max-width: 768px) {
    /* Target collapsible rows for mobile */
    tr.collapsible td:last-child::after {
      right: 5px;
      font-size: 10px;
    }
  }
  
  /* Safari-specific fixes */
  @supports (-webkit-appearance: none) {
    tr.collapsible td:last-child {
      overflow: visible;
    }
    
    /* Force hardware acceleration for Safari */
    tr.collapsible td:last-child::after {
      -webkit-transform: translateY(-50%);
      -webkit-backface-visibility: hidden;
      -webkit-perspective: 1000px;
    }
    
    tr.collapsible.collapsed td:last-child::after {
      -webkit-transform: translateY(-50%) rotate(-90deg);
    }
  }
</style>

## Program Overview

<style>
.day-header-detailed {
position: sticky;
    top: 0px;
  background-color: #f5f5f5;
  padding: 4px;
  text-align: center;
  font-weight: bold;
  font-size: 1.2em;
  border-bottom: 1px solid #ddd;
  height: 30px;
  min-width: 300px;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  line-height: 1.1;
}

.time-axis {
  display: flex;
  flex-direction: column;
  border-right: 2px solid #ddd;
  background-color: #f5f5f5;
  width: 80px;
  flex-shrink: 0;
}

@media (max-width: 768px) {
  .time-axis {
    width: 30px;
    font-size: 0.75em;
  }
}

.time-slot {
  text-align: center;
  padding: 4px;
  font-size: 0.7em;
  font-weight: bold;
  border-bottom: 1px solid #ddd;
  height: 30px;
  display: flex;
  align-items: center;
  justify-content: center;
}

.day-columns {
  display: flex;
  gap: 1px;
  background-color: #ddd;
  flex: 1;
}

.day-column {
  flex: 1;
  background-color: #fff;
  min-height: 600px;
  position: relative;
}

.day-header {
  background-color: #f5f5f5;
  padding: 4px;
  text-align: center;
  font-weight: bold;
  font-size: 0.6em;
  border-bottom: 1px solid #ddd;
  height: 50px;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  line-height: 1.1;
}

.event-block {
  position: absolute;
  background-color: var(--event-color);
  box-shadow: 0px -4px 12px rgba(47, 10, 10, 0.2);
  border: 1px solid #ccc;
  border-radius: 4px;
  padding: 4px 4px;
  font-size: 0.7em;
  color: #333;
  cursor: pointer;
  overflow: hidden;
  text-overflow: ellipsis;
  white-space: normal;
  line-height: 1.3;
  min-height: 30px; 
  width: calc(100% - 16px);
  margin: 0 8px;
  transition: all 0.3s ease;
  z-index: 1;
  word-wrap: break-word;
}

@media (max-width: 768px) {
  .event-block {
    margin: 0 2px;
    width: calc(100% - 4px);
  }
}

.event-block:hover {
  z-index: 1000;
  transform: scale(1.00);
  box-shadow: 0 4px 12px rgba(0,0,0,0.4);
  overflow: visible;
  white-space: normal;
  width: calc(100% - 16px);
  min-width: calc(100% - 16px);
  max-width: calc(100% - 16px);
  word-wrap: break-word;
  height: auto;
  min-height: 20px;
  padding: 6px 4px;
}

/* Event type styling */
.event-phd-school {
  background-color: #f3e3df;
  color: #2C2C2C;
  border-left: 4px solid #A34D3A;
}

.event-logistical {
  background-color: #FFE9AB;
  color: #2C2C2C;
  border-left: 4px solid #FFD700;
}

.event-other {
  background-color:rgb(255, 254, 241);
  color: #2C2C2C;
  border-left: 4px solid rgb(248, 234, 156);
}

.event-logistical-highlight {
  background-color: rgb(248, 207, 92);
  color: #2C2C2C;
  border-left: 4px solid #FFD700;
}

.event-session {
  background-color: #dab3aa;
  color: #2C2C2C;
  border-left: 4px solid #843F30;
}

.event-special {
  background-color: rgb(162, 229, 248);
  color: #2C2C2C;
  border-left: 4px solid #42B5D5;
}

.event-special-highlight {
  background-color: rgb(84, 207, 241);
  color: #2C2C2C;
  border-left: 4px solid #42B5D5;
}

.event-invited {
  background-color: rgb(162, 229, 248);
  color: #2C2C2C;
  border-left: 4px solid #42B5D5;
}

.event-title {
  font-weight: bold;
  margin-bottom: 2px;
  font-size: 0.8em;
}

.event-time {
  font-size: 0.7em;
  opacity: 0.8;
  font-weight: bold;
  margin: 2px 0;
}

.event-location {
  font-size: 0.7em;
  opacity: 0.7;
  font-style: italic;
  margin: 1px 0;
}

.event-sponsor {
  font-size: 0.7em;
  opacity: 0.9;
  font-weight: bold;
  margin: 1px 0;
}

.event-speaker {
  font-size: 0.7em;
  opacity: 0.8;
  margin: 1px 0;
}

.event-details {
  font-size: 0.65em;
  opacity: 0.7;
  margin-top: 2px;
}

@media (max-width: 768px) {
  .event-block {
    font-size: 0.7em;
    padding: 4px 6px;
  }
}
</style>
<p style="font-size: 0.7em;">Please hover over events to view details</p>

<div class="timeline-container">
  <div style="display: flex;">
    <div class="time-axis" id="timeAxis">
    </div>
    <div class="day-columns" id="dayColumns">
    </div>
  </div>
</div>

<script>
const timelineData = {
  timeRange: { start: "08:30", end: "22:30" },
  days: [
    {
      name: "Monday",
      date: "Aug 17",
      events: [
        { start: "08:30", end: "09:00", type: "logistical", title: "Registration (PhD School)", location: "TBA" },
        { start: "09:00", end: "12:00", type: "phd-school", title: "PhD School", speaker: "Lectures and Coffee Break"},
        //{ start: "10:30", end: "11:00", type: "logistical", title: "Coffee Break" },
        { start: "12:00", end: "14:00", type: "other", title: "Lunch Break" },
        { start: "14:00", end: "17:00", type: "phd-school", title: "PhD School", speaker: "Lectures and Coffee Break"}
        //{ start: "14:00", end: "17:00", type: "phd-school", title: "PhD School", speaker: "Markus Chimani", location: "TP42, Campus Norrköping", details: "Crossing number: Complexity and Algorithms", link: "../school/#markus-chimani" },
        //{ start: "15:30", end: "16:00", type: "logistical", title: "Coffee Break" }
      ]
    },
    {
      name: "Tuesday",
      date: "Aug 18",
      events: [
        { start: "09:00", end: "12:00", type: "phd-school", title: "PhD School", speaker: "Lectures and Coffee Break"},
        //{ start: "10:30", end: "11:00", type: "logistical", title: "Coffee Break" },
        { start: "12:00", end: "14:00", type: "other", title: "Lunch Break" },
        { start: "14:00", end: "16:00", type: "phd-school", title: "PhD School", speaker: "Lectures and Coffee Break"},
        //{ start: "15:30", end: "16:00", type: "logistical", title: "Coffee Break" },
        { start: "18:30", end: "20:30", type: "logistical-highlight", title: "Conference Welcome Reception", location: "TBA" }
      ]
    },
    {
      name: "Wednesday",
      date: "Aug 19",
      events: [
        { start: "08:30", end: "09:00", type: "logistical", title: "Registration", location: "" },
        { start: "09:00", end: "09:15", type: "special", title: "Opening", location: "" },
        { start: "09:15", end: "10:30", type: "session", title: "Session 1", location: "", speaker: "Chair: TBA" },
        { start: "10:30", end: "11:00", type: "logistical", title: "Coffee Break", location: "" },
        { start: "11:00", end: "12:20", type: "session", title: "Session 2", location: "", speaker: "Chair: TBA" },
        { start: "12:20", end: "14:00", type: "logistical", title: "Lunch", location: "" },
        { start: "14:00", end: "15:00", type: "special", title: "Posters", location: "" },
        { start: "15:00", end: "15:30", type: "logistical", title: "Coffee Break", location: "" },
        { start: "15:30", end: "16:30", type: "session", title: "Session 3", location: "", speaker: "Chair: TBA", details: "" },
        { start: "16:30", end: "18:00", type: "special-highlight", title: "GDC Live Challenge", location: "", link: "https://mozart.diei.unipg.it/gdcontest/2026/" }
      ]
    },
    {
      name: "Thursday",
      date: "Aug 20",
      events: [
        { start: "09:00", end: "10:30", type: "session", title: "Session 4", location: "", speaker: "Chair: TBA" },
        { start: "10:30", end: "11:00", type: "logistical", title: "Coffee Break", location: "" },
        { start: "11:00", end: "12:20", type: "session", title: "Session 5", location: "", speaker: "Chair: TBA", sponsor: "" },
        { start: "12:20", end: "14:00", type: "logistical", title: "Lunch", location: "" },
        { start: "14:00", end: "15:00", type: "invited", title: "Invited Talk", speaker: "Chair: TBA", location: "", details: "" },
        { start: "15:00", end: "15:30", type: "logistical", title: "Coffee Break", location: "" },
        { start: "15:30", end: "16:30", type: "session", title: "Session 6", location: "", speaker: "Chair: TBA", sponsor: "" },
        { start: "16:30", end: "17:30", type: "special-highlight", title: "Business Meeting", location: "Location: TBA" },
        { start: "17:30", end: "23:00", type: "logistical-highlight", title: "Social Dinner", location: "Queen Victoria Place, Niagara Falls" }
      ]
    },
    {
      name: "Friday",
      date: "Aug 21",
      events: [
        { start: "09:00", end: "10:30", type: "session", title: "Session 7", location: "", speaker: "Chair: TBA" },
        { start: "10:30", end: "11:00", type: "logistical", title: "Coffee Break", location: "" },
        { start: "11:00", end: "12:20", type: "session", title: "Session 8", location: "", speaker: "Chair: TBA", sponsor: "" },
        { start: "12:20", end: "14:00", type: "logistical", title: "Lunch", location: "" },
        { start: "14:00", end: "15:00", type: "invited", title: "Invited Talk", speaker: "Chair: TBA", location: "", details: "" },
        { start: "15:00", end: "15:30", type: "logistical", title: "Coffee Break", location: "Location: TBA" },
        { start: "15:30", end: "16:30", type: "session", title: "Session 9", location: "", speaker: "Chair: TBA" },
        { start: "16:30", end: "17:00", type: "special", title: "Closing & Awards", location: "" }
      ]
    }
  ]
};

// Convert time string to minutes since midnight
function timeToMinutes(timeStr) {
  const [hours, minutes] = timeStr.split(':').map(Number);
  return hours * 60 + minutes;
}

// Convert minutes to time string
function minutesToTime(minutes) {
  const hours = Math.floor(minutes / 60);
  const mins = minutes % 60;
  return `${hours.toString().padStart(2, '0')}:${mins.toString().padStart(2, '0')}`;
}

// Generate time axis (vertical on the left)
function generateTimeAxis() {
  const timeAxis = document.getElementById('timeAxis');
  const startMinutes = timeToMinutes(timelineData.timeRange.start);
  const endMinutes = timeToMinutes(timelineData.timeRange.end);
  const totalMinutes = endMinutes - startMinutes;
  const containerHeight = 1100; // Same as in generateDayColumns
  const pixelsPerMinute = containerHeight / totalMinutes;
  
  timeAxis.innerHTML = '<div class="time-slot" style="height: 50px; font-weight: bold;">Time</div>';
  
  for (let minutes = startMinutes; minutes <= endMinutes; minutes += 30) {
    const timeStr = minutesToTime(minutes);
    const timeSlot = document.createElement('div');
    timeSlot.className = 'time-slot';
    timeSlot.textContent = timeStr;
    
    // Calculate height to match event block positioning
    const slotHeight = 30 * pixelsPerMinute; // 30 minutes = 30 * pixelsPerMinute
    timeSlot.style.height = `${slotHeight}px`;
    
    timeAxis.appendChild(timeSlot);
  }
}

// Generate day columns with proportional event blocks
function generateDayColumns() {
  const dayColumns = document.getElementById('dayColumns');
  const startMinutes = timeToMinutes(timelineData.timeRange.start);
  const endMinutes = timeToMinutes(timelineData.timeRange.end);
  const totalMinutes = endMinutes - startMinutes;
  const containerHeight = 1100; // Base height in pixels
  const pixelsPerMinute = containerHeight / totalMinutes;
  const headerHeight = 50; // Height of the day header
  
  dayColumns.innerHTML = '';
  
  timelineData.days.forEach(day => {
    const dayColumn = document.createElement('div');
    dayColumn.className = 'day-column';
    
    // Add day header
    const header = document.createElement('div');
    header.className = 'day-header';
    header.innerHTML = `${day.name}<br>${day.date}`;
    dayColumn.appendChild(header);
    
    // Add event blocks
    day.events.forEach(event => {
      const eventBlock = document.createElement('div');
      eventBlock.className = `event-block event-${event.type}`;
      
      // Calculate position and height based on actual time
      const startMin = timeToMinutes(event.start);
      const endMin = timeToMinutes(event.end);
      
      // Align with time axis: start from header height, then calculate position
      const top = headerHeight + ((startMin - startMinutes) * pixelsPerMinute);
      let height = ((endMin - startMin) * pixelsPerMinute);
      
      // Special case: ensure minimum height for very short events like "Opening"
      if (event.title === "Opening" || height < 40) {
        height = Math.max(height, 40); // Minimum 40px height
      }
      
      eventBlock.style.top = `${top}px`;
      eventBlock.style.height = `${height}px`;
      
      // Build event content
      let content = `<div class="event-title">`;
      if (event.link) {
        content += `<a href="${event.link}">${event.title}</a>`;
      } else {
        content += event.title;
      }
      content += `</div>`;
        if (event.sponsor) {
        content += `<div class="event-sponsor">Sponsored by ${event.sponsor}</div>`;
      }
      
      content += `<div class="event-time">${event.start}-${event.end}</div>`;


      if (event.speaker) {
        content += `<div class="event-speaker">${event.speaker}</div>`;
      }
      
      
      if (event.location) {
        content += `<div class="event-location">${event.location}</div>`;
      }
      

      if (event.details) {
        content += `<div class="event-details">${event.details}</div>`;
      }
      
      eventBlock.innerHTML = content;
      
      // Special styling for Opening event
      if (event.title === "Opening") {
        eventBlock.style.padding = "2px 4px"; 
        eventBlock.style.fontSize = "0.7em"; 
        // eventBlock.style.fontWeight = "bold"; 
      }
      
   // Add click handler
        eventBlock.onclick = () => {
            const dayId = day.name.toLowerCase();
            scrollToSection(dayId);
        };
      
      // Add hover handlers for dynamic height adjustment
      eventBlock.addEventListener('mouseenter', function() {
        // Store original height
        this.setAttribute('data-original-height', this.style.height);
        
        // Temporarily set styles to measure full content
        const originalOverflow = this.style.overflow;
        const originalHeight = this.style.height;
        
        this.style.overflow = 'visible';
        this.style.height = 'auto';
        
        // Calculate full content height including padding and borders
        const rect = this.getBoundingClientRect();
        const computedStyle = window.getComputedStyle(this);
        const paddingTop = parseFloat(computedStyle.paddingTop);
        const paddingBottom = parseFloat(computedStyle.paddingBottom);
        const borderTop = parseFloat(computedStyle.borderTopWidth);
        const borderBottom = parseFloat(computedStyle.borderBottomWidth);
        
        // Get the actual content height
        const contentHeight = this.scrollHeight;
        const totalHeight = contentHeight + paddingTop + paddingBottom + borderTop + borderBottom;
        
        // Set the calculated height
        this.style.height = totalHeight + 'px';
        this.style.overflow = 'visible';
      });
      
      eventBlock.addEventListener('mouseleave', function() {
        // Restore original height
        const originalHeight = this.getAttribute('data-original-height');
        this.style.height = originalHeight;
        this.style.overflow = 'hidden';
      });
      
      dayColumn.appendChild(eventBlock);
    });
    
    dayColumns.appendChild(dayColumn);
  });
}

// Initialize the timeline
document.addEventListener('DOMContentLoaded', function() {
  generateTimeAxis();
  generateDayColumns();
});

// Function to scroll to specific sections (existing)
function scrollToSection(sectionId) {
  const element = document.getElementById(sectionId);
  if (element) {
    element.scrollIntoView({ 
      behavior: 'smooth', 
      block: 'start' 
    });
  }
}
</script>

## Detailed Schedule

<p>Jump to <a href="#monday">Monday</a>, <a href="#tuesday">Tuesday</a>, <a href="#wednesday">Wednesday</a>, <a href="#thursday">Thursday</a>, or <a href="#friday">Friday</a>.</p>

<p><em>[T1] Track 1 Paper</em>, <em>[T2] Track 2 Paper</em></p>
<table id="monday">
  <colgroup>
    <col width="25%" />
    <col width="75%" />
  </colgroup>
  <thead class="day-header-detailed">
    <tr><th colspan="2">Monday, August 17</th></tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>Time</strong></td>
      <td><strong>Event</strong></td>
    </tr>
    <tr class="registration">
      <td>08:30 &mdash; 09:00</td>
      <td>PhD School Registration, <span class="Location-info">Location: TBA</span></td>
    </tr>
    <tr class="phd-school">
      <td>09:00 &mdash; 10:30</td>
      <td>Lecture by Prof. Dr. Myroslav Kryven</td>
    </tr>
    <tr class="coffee">
      <td>10:30 &mdash; 11:00</td>
      <td>Coffee Break</td>
    </tr>
    <tr class="phd-school">
      <td>11:00 &mdash; 12:30</td>
      <td>Lecture by Prof. Dr. Alessandra Tappini</td>
    </tr>
    <tr>
      <td>12:30 &mdash; 14:00</td>
      <td>Lunch Break</td>
    </tr>
    <tr class="phd-school">
      <td>14:00 &mdash; 15:30</td>
      <td>Lecture by Prof. Dr. Reyan Ahmed</td>
    </tr>
    <tr class="coffee">
      <td>15:30 &mdash; 16:00</td>
      <td>Coffee Break</td>
    </tr>
    <tr class="phd-school">
      <td>16:00 &mdash; 17:00</td>
      <td>Experiments and Discussion by Prof. Dr. Reyan Ahmed</td>
    </tr>
  </tbody>
</table>

<hr>

<table id="tuesday">
  <colgroup>
    <col width="25%"/>
    <col width="75%"/>
  </colgroup>
  <thead class="day-header-detailed">
    <tr><th colspan="2">Tuesday, August 18</th></tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>Time</strong></td>
      <td><strong>Event</strong></td>
    </tr>
    <tr class="registration">
      <td>08:30 &mdash; 09:00</td>
      <td>PhD School Registration, <span class="Location-info">Location: TBA</span></td>
    </tr>
    <tr class="phd-school">
      <td>09:00 &mdash; 10:30</td>
      <td>Lecture by Prof. Dr. Md. Saidur Rahman</td>
    </tr>
    <tr class="coffee">
      <td>10:30 &mdash; 11:00</td>
      <td>Coffee Break</td>
    </tr>
    <tr class="phd-school">
      <td>11:00 &mdash; 12:30</td>
      <td>Lecture by Prof. Dr. Carola Wenk</td>
    </tr>
    <tr>
      <td>12:30 &mdash; 14:00</td>
      <td>Lunch Break</td>
    </tr>
    <tr class="phd-school">
      <td>14:00 &mdash; 15:30</td>
      <td>Lecture by Prof. Dr. Will Evans</td>
    </tr>
    <tr class="coffee">
      <td>15:30 &mdash; 16:00</td>
      <td>Coffee Break and Conclusion of PhD School</td>
    </tr> 
    <tr class="reception">
      <td>18:30 &mdash; 20:30</td>
      <td>Conference Welcome Reception, <span class="Location-info">Location: TBA</span></td>
    </tr>
  </tbody>      
</table>

<hr>

<table id="wednesday">
  <colgroup>
    <col width="25%" />
    <col width="75%" />
  </colgroup>
  <thead class="day-header-detailed">
    <tr><th colspan="2">Wednesday, August 19</th></tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>Time</strong></td>
      <td><strong>Event</strong></td>
    </tr>
    <tr class="registration">
      <td>08:30 &mdash; 09:00</td>
      <td>Registration, <span class="Location-info">Location: TBA</span></td>
    </tr>
    <tr class="poster">
      <td>09:00 &mdash; 09:10</td>
      <td>Opening</td>
    </tr>
    <tr class="session header schedule-link" id="session-1" schedule-link-start="2026-08-19T09:15" schedule-link-end="2026-08-19T10:30" schedule-link-text="Session 1">
      <td><strong>Session 1,<br> 09:10 &mdash; 10:30</strong></td>
      <td><strong>Chair: TBA, <span class="Location-info">Location: TBA</span></strong></td>
    </tr>
    <tr class="session">
      <td>09:10 &mdash; 09:30</td>
      <td><span class="authors">Sergey Pupyrev</span>. <span class="title">How to Draw a Planar Graph: An Experimental Evaluation</span> <span class="slides-link"><a href="" target="_blank"> </a></span> <span class="track">[T2]</span></td>
    </tr>
    <tr class="session light">
      <td>09:30 &mdash; 09:50</td>
      <td><span class="authors">Giordano Andreola, Susanna Caroppo, Giordano Da Lozzo, Marco D'Elia, Giuseppe Di Battista, Fabrizio Frati, Fabrizio Grosso and Maurizio Patrignani</span>. <span class="title">Extending Biconnected Straight-Line Planar Drawings</span> <span class="slides-link"><a href="" target="_blank"> </a></span> <span class="track">[T1]</span></td>
    </tr>
    <tr class="session">
      <td>09:50 &mdash; 10:10</td>
      <td><span class="authors">Patrizio Angelini, Sabine Cornelsen, Giordano Da Lozzo, Seok-Hee Hong and Ignaz Rutter</span>. <span class="title">Beyond Degree Four: Near-Orthogonal Planar Drawings</span> <span class="slides-link"><a href="" target="_blank"> </a></span> <span class="track">[T1]</span></td>
    </tr>
    <tr class="session light">
      <td>10:10 &mdash; 10:30</td>
      <td><span class="authors">Vera Chekan, Robert Ganian and Viktoriia Korchemna</span>. <span class="title">A Fixed-Parameter Algorithm for Extending Upward Planar Drawings</span> <span class="slides-link"><a href="" target="_blank"> </a></span><span class="track">[T1]</span></td>
    </tr>
    <tr class="coffee">
      <td>10:30 &mdash; 11:00</td>
      <td>Coffee Break, <span class="Location-info">Location: TBA</span></td>
    </tr>
    <tr class="session header schedule-link" id="session-2" schedule-link-start="2026-08-19T11:00" schedule-link-end="2026-08-19T12:20" schedule-link-text="Session 2">
      <td><strong>Session 2,<br> 11:00 &mdash; 12:20</strong></td>
      <td><strong>Chair: TBA, <span class="Location-info">Location: TBA</span></strong></td>
    </tr>
    <tr class="session">
      <td>11:00 &mdash; 11:20</td>
      <td><span class="authors">Markus Wallinger, Oscar Navarro and Stephen Kobourov</span>. <span class="title">Minimum-Width Drawings of Trees with Sized Vertices</span> <span class="slides-link"><a href="" target="_blank"> </a></span><span class="track">[T2]</span></td>
    </tr>
    <tr class="session light">
      <td>11:20 &mdash; 11:40</td>
      <td><span class="authors">Anna Lubiw and Marcus Schaefer</span>. <span class="title">Recognizing Penny and Marble Graphs is Hard for Existential Theory of the Reals</span> <span class="slides-link"><a href="" target="_blank"> </a></span> <span class="track">[T1]</span></td>
    </tr>
    <tr class="session">
      <td>11:40 &mdash; 12:00</td>
      <td><span class="authors">Todor Antić, Jiří Fiala, Jelena Glišić, Grzegorz Gutowski, Konstanty Junosza-Szaniawski, Jan Kratochvíl, Giuseppe Liotta, Morteza Saghafian, Maria Saumell, Krisztina Szilágyi and Pavel Valtr</span>. <span class="title">How Close is a Tree to a Euclidean Minimum Spanning Tree?</span> <span class="slides-link"><a href="" target="_blank"> </a></span> <span class="track">[T1]</span></td>
    </tr>
    <tr class="session light">
      <td>12:00 &mdash; 12:20</td>
      <td><span class="authors">Thomas Depian, Thomas C. Van Dijk and Martin Nöllenburg</span>. <span class="title">Paged Geophylogenies: A Coloring Approach to External Labeling with Tree Constraints</span> <span class="slides-link"><a href="" target="_blank"> </a></span> <span class="track">[T2]</span></td>
    </tr>
    <tr class="lunch">
      <td>12:20 &mdash; 14:00</td>
      <td>Lunch, <span class="Location-info">Location: TBA</span></td>
    </tr>
    <tr class="poster">
      <td>14:00 &mdash; 15:00</td>
      <td>
        <ul class="poster-list">
          <li>Posters: TBA</li>
        </ul>
      </td>
    </tr>
    <tr class="coffee">
      <td>15:00 &mdash; 15:30</td>
      <td>Coffee Break, <span class="Location-info">Location: TBA</span></td>
    </tr>
    <tr class="session header schedule-link" id="session-3" schedule-link-start="2026-08-19T15:30" schedule-link-end="2026-08-19T16:30" schedule-link-text="Session 3">
      <td><strong>Session 3,<br> 15:30 &mdash; 16:30</strong></td>
      <td><strong>Chair: TBA, <span class="Location-info">Location: TBA</span></strong></td>
    </tr>
    <tr class="session">
      <td>15:30 &mdash; 15:50</td>
      <td><span class="authors">Stefan Felsner, Jędrzej Hodor, Giacomo Ortali and Alexander Wolff</span>. <span class="title">Navigating Posets with Few Maps</span> <span class="slides-link"><a href="" target="_blank"> </a></span> <span class="track">[T1]</span></td>
    </tr>
    <tr class="session light">
      <td>15:50 &mdash; 16:10</td>
      <td><span class="authors">Marcel Nöhre and Gerd Stumme</span>. <span class="title">Node Labeling in Line Diagrams of Ordered Sets</span> <span class="slides-link"><a href="" target="_blank"> </a></span> <span class="track">[T2]</span></td>
    </tr>
    <tr class="session">
      <td>16:10 &mdash; 16:30</td>
      <td><span class="authors">Michael A. Bekos, Carla Binucci, Emilio Di Giacomo, Walter Didimo, Luca Grilli, Maria Eleni Pavlidi, Alessandra Tappini and Alexandra Weinberger</span>. <span class="title">Stack and Queue Layouts with Defects</span> <span class="slides-link"><a href="" target="_blank"> </a></span> <span class="track">[T1]</span></td>
    </tr>
    <tr class="gdc schedule-link" id="gdc" schedule-link-start="2026-08-19T16:30" schedule-link-end="2026-08-19T18:00" schedule-link-text="GDC Live Challenge">
      <td><strong>17:00 &mdash; 18:30</strong></td>
      <td><strong><a href="https://mozart.diei.unipg.it/gdcontest/2026/" target="_blank">GDC Live Challenge</a>, <span class="Location-info">Location: TBA</span></strong></td>
    </tr>
  </tbody>
</table>

<hr>

<table id="thursday">
  <colgroup>
    <col width="25%" />
    <col width="75%" />
  </colgroup>
  <thead class="day-header-detailed">
    <tr><th colspan="2">Thursday, August 20</th></tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>Time</strong></td>
      <td><strong>Event</strong></td>
    </tr>
    <tr class="session header schedule-link" id="session-4" schedule-link-start="2026-08-20T09:00" schedule-link-end="2026-08-20T10:30" schedule-link-text="Session 4">
      <td><strong>Session 4,<br> 09:00 &mdash; 10:30</strong></td>
      <td><strong>Chair: TBA, <span class="Location-info">Location: TBA</span></strong></td>
    </tr>
    <tr class="session">
      <td>09:00 &mdash; 09:20</td>
      <td><span class="authors">Simon D. Fink, Matthias Pfretzschner, Ignaz Rutter and Marie Diana Sieper</span>. <span class="title">Monotone Clustered Level Planarity</span> <span class="track">[T1]</span></td>
    </tr>
    <tr class="session light">
      <td>09:20 &mdash; 09:40</td>
      <td><span class="authors">Saeed Odak, Jonathan Rollin and Torben Scheele</span>. <span class="title">On 2-Layer k-Matching-Planar Graphs</span> <span class="track">[T1]</span></td>
    </tr>
    <tr class="session">
      <td>09:40 &mdash; 10:00</td>
      <td><span class="authors">Alexander Firbas, Robert Ganian, Sylvain Meunier and Martin Nöllenburg</span>. <span class="title">Two-Layer Drawings with a Tree on Top: Vertex Splits and Fixed-Parameter Algorithms</span> <span class="track">[T1]</span></td>
    </tr>
    <tr class="session light">
      <td>10:00 &mdash; 10:15</td>
      <td><span class="authors">Yasuaki Kobayashi and Yuto Okada</span>. <span class="title">2-Layer Fan-Planarity in Polynomial Time</span> <span class="track">[T1, short]</span></td>
    </tr>
    <tr class="session">
      <td>10:15 &mdash; 10:30</td>
      <td><span class="authors">Alexander Dobler, Siddharth Gupta, Philipp Kindermann, Fabrizio Montecchiani and Martin Nöllenburg</span>. <span class="title">On the Complexity of Extending Storylines</span> <span class="track">[T1, short]</span></td>
    </tr>
    <tr class="coffee">
      <td>10:30 &mdash; 11:00</td>
      <td>Coffee Break, <span class="Location-info">Location: TBA</span></td>
    </tr>
    <tr class="session header schedule-link" id="session-5" schedule-link-start="2026-08-20T11:00" schedule-link-end="2026-08-20T12:20" schedule-link-text="Session 5">
      <td><strong>Session 5,<br> 11:00 &mdash; 12:20</strong></td>
      <td><strong>Sponsored by <a href="" style="color: white !important">TBA</a>, <br>Chair: TBA, <span class="Location-info">Location: TBA</span></strong></td>
    </tr>
    <tr class="session">
      <td>11:00 &mdash; 11:20</td>
      <td><span class="authors">Sara Di Bartolomeo, Fabrizio Montecchiani and Andrea Tomassoni</span>. <span class="title">Clic: Highlighting Clique Motifs in Biofabric Visualizations</span> <span class="track">[T2]</span></td>
    </tr>
    <tr class="session light">
      <td>11:20 &mdash; 11:40</td>
      <td><span class="authors">Michal Katrlík</span>. <span class="title">Tight Leading-Term Bounds for the Z2-Genus of Complete Graphs</span> <span class="track">[T1]</span></td>
    </tr>
    <tr class="session">
      <td>11:40 &mdash; 12:00</td>
      <td><span class="authors">Alexandra Weinberger and Ji Zeng</span>. <span class="title">What induces plane structures in complete graph drawings?</span> <span class="track">[T1]</span></td>
    </tr>
    <tr class="session light">
      <td>12:00 &mdash; 12:20</td>
      <td><span class="authors">Stefan Felsner</span>. <span class="title">Antipodal Pairs and Crossing Numbers</span> <span class="track">[T1]</span></td>
    </tr>
    <tr class="lunch">
      <td>12:20 &mdash; 14:00</td>
      <td>Lunch, <span class="Location-info">Location: TBA</span></td>
    </tr>
    <tr class="invited-talk schedule-link" id="invited-talk-Hans-Bodlaender" schedule-link-start="2026-08-20T14:00" schedule-link-end="2026-08-20T15:00" schedule-link-text="Invited Talk">
      <td>14:00 &mdash; 15:00</td>
      <td><strong>Invited Talk</strong>, <span class="Location-info">Location: TBA</span><br><span class="title"><br><strong>Chair: TBA</strong></span></td>
    </tr>
    <tr class="coffee">
      <td><strong>15:00 &mdash; 15:30</strong></td>
      <td><strong>Coffee Break, <span class="Location-info">Location: TBA</span></strong></td>
    </tr>
    <tr class="session header schedule-link" id="session-6" schedule-link-start="2026-08-20T15:30" schedule-link-end="2026-08-20T16:30" schedule-link-text="Session 6">
      <td><strong>Session 6,<br> 15:30 &mdash; 16:30</strong></td>
      <td><strong>Sponsored by <a href="" target="_blank" style="color: white !important">TBA</a>, <br>Chair: TBA, <span class="Location-info">Location: TBA</span></strong></td>
    </tr>
    <tr class="session">
      <td>15:30 &mdash; 15:50</td>
      <td><span class="authors">Alessandro Palma, Sara Di Bartolomeo and Marco Angelini</span>. <span class="title">Weaving (Bio)fabric: A Benchmark for Scalability through Progressive Sampling Methods</span> <span class="track">[T2]</span></td>
    </tr>
    <tr class="session light">
      <td>15:50 &mdash; 16:10</td>
      <td><span class="authors">Timo Brand, Henry Förster, Stephen Kobourov, Daniel Kohrt, Robin Schukrafft, Markus Wallinger and Johannes Zink</span>. <span class="title">Using Reinforcement Learning to Optimize the Global and Local Crossing Number</span> <span class="track">[T2]</span></td>
    </tr>
    <tr class="session">
      <td>16:10 &mdash; 16:30</td>
      <td><span class="authors">Gavin J. Mooney, Michael Wybrow and Helen C. Purchase</span>. <span class="title">Does graph structure affect drawing quality?</span> <span class="track">[T2]</span></td>
    </tr>
    <tr class="business-meeting">
      <td><strong>16:30 &mdash; 17:30</strong></td>
      <td><strong>Business Meeting, <span class="Location-info">Location: TBA</span></strong></td>
    </tr>
    <tr class="reception">
      <td>17:30 &mdash; 23:00</td>
      <td>Social Dinner, <span class="Location-info"><a href="https://www.niagaraparks.com/visit/culinary/queen-victoria-place-restaurant/" target="_blank">Queen Victoria Place, Niagara Falls</a></span></td>
    </tr>
  </tbody>
</table>

<hr>

<table id="friday">
  <colgroup>
    <col width="25%" />
    <col width="75%" />
  </colgroup>
  <thead class="day-header-detailed">
    <tr><th colspan="2">Friday, August 21</th></tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>Time</strong></td>
      <td><strong>Event</strong></td>
    </tr>
    <tr class="session header schedule-link" id="session-7" schedule-link-start="2026-08-21T09:00" schedule-link-end="2026-08-21T10:30" schedule-link-text="Session 7">
      <td><strong>Session 7,<br> 09:00 &mdash; 10:30</strong></td>
      <td><strong>Chair: TBA, <span class="Location-info">Location: TBA</span></strong></td>
    </tr>
    <tr class="session">
      <td>09:00 &mdash; 09:20</td>
      <td><span class="authors">Kazuo Misue and Naoto Kikuta</span>. <span class="title">Opacity-Modulated Edge Drawing</span> <span class="track">[T2]</span></td>
    </tr>
    <tr class="session light">
      <td>09:20 &mdash; 09:40</td>
      <td><span class="authors">Henry Förster, Michael Hoffmann, Stephen Kobourov, Maria Eleni Pavlidi, Alexandra Weinberger and Johannes Zink</span>. <span class="title">Weighted Book Thickness</span> <span class="track">[T1]</span></td>
    </tr>
    <tr class="session">
      <td>09:40 &mdash; 10:00</td>
      <td><span class="authors">Todor Antić, Vít Jelínek, Jan Kratochvíl and Peter Stumpf</span>. <span class="title">Two Results on Outer-String Graphs</span> <span class="track">[T1]</span></td>
    </tr>
    <tr class="session">
      <td>10:10 &mdash; 10:15</td>
      <td><span class="authors">Robert Ganian, Philipp Mauve and Vaishali Surianarayanan</span>. <span class="title">Circle Graph 3-Coloring: Can Simplicity Beat SAT?</span> <span class="track">[T2, short]</span></td>
    </tr>
    <tr class="session light">
      <td>10:15 &mdash; 10:30</td>
      <td><span class="authors">Amyra Meidiana and Seok-Hee Hong</span>. <span class="title">Fast UMAP-based Graph Drawing</span> <span class="track">[T2, short]</span></td>
    </tr>
    <tr class="coffee">
      <td><strong>10:30 &mdash; 11:00</strong></td>
      <td><strong>Coffee Break, <span class="Location-info">Location: TBA</span></strong></td>
    </tr>
    <tr class="session header schedule-link" id="session-8" schedule-link-start="2026-08-21T11:00" schedule-link-end="2026-08-21T12:20" schedule-link-text="Session 8">
      <td><strong>Session 8,<br> 11:00 &mdash; 12:20</strong></td>
      <td><strong>Chair: TBA, <span class="Location-info">Location: TBA</span></strong></td>
    </tr>
    <tr class="session">
      <td>11:00 &mdash; 11:20</td>
      <td><span class="authors">Stefan Felsner, Kolja Knauer, Yasumi Kogo and Bobby Miraftab</span>. <span class="title">1-Planar Drawings of Products of Cycles</span> <span class="track">[T1]</span></td>
    </tr>
    <tr class="session light">
      <td>11:20 &mdash; 11:40</td>
      <td><span class="authors">Michael A. Bekos, Eleni Katsanou, Philipp Kindermann, Aikaterini Maria Ntasiou, Maria Eleni Pavlidi and Soeren Terziadis</span>. <span class="title">On the 2-Bend Slope Number of 1-Planar Graphs</span> <span class="track">[T1]</span></td>
    </tr>
    <tr class="session">
      <td>11:40 &mdash; 12:00</td>
      <td><span class="authors">Aaron Büngener, Jakob Franz, Michael Kaufmann and Maximilian Pfister</span>. <span class="title">A first view on the density of 5-planar graphs</span> <span class="track">[T1]</span></td>
    </tr>
    <tr class="session light">
      <td>12:00 &mdash; 12:20</td>
      <td><span class="authors">Miriam Goetze, Michael Kaufmann and Soeren Terziadis</span>. <span class="title">On t-colorable k-plane drawings</span> <span class="track">[T1]</span></td>
    </tr>
    <tr class="lunch">
      <td><strong>12:20 &mdash; 14:00</strong></td>
      <td><strong>Lunch, <span class="Location-info">Location: TBA</span></strong></td>
    </tr>
    <tr class="invited-talk schedule-link" id="invited-talk-huamin" schedule-link-start="2026-08-21T14:00" schedule-link-end="2026-08-21T15:00" schedule-link-text="Invited Talk">
      <td>14:00 &mdash; 15:00</td>
      <td><strong>Invited Talk</strong>, <span class="Location-info">Location: TBA</span><br> <span class="title"><br><strong>Chair: TBA</strong></span></td>
    </tr>
    <tr class="coffee">
      <td><strong>15:00 &mdash; 15:30</strong></td>
      <td><strong>Coffee Break, <span class="Location-info">Location: TBA</span></strong></td>
    </tr>
    <tr class="session header schedule-link" id="session-9" schedule-link-start="2026-08-21T15:30" schedule-link-end="2026-08-21T16:30" schedule-link-text="Session 9">
      <td><strong>Session 9,<br> 15:30 &mdash; 16:30</strong></td>
      <td><strong>Chair: TBA, <span class="Location-info">Location: TBA</span></strong></td>
    </tr>
    <tr class="session">
      <td>15:30 &mdash; 15:50</td>
      <td><span class="authors">Thomas Depian, Joseph Dorfer, Boris Klemz, Matthias Pfretzschner and Lena Schlipf</span>. <span class="title">Point Set Embeddability with List Constraints</span> <span class="track">[T1]</span></td>
    </tr>
    <tr class="session light">
      <td>15:50 &mdash; 16:10</td>
      <td><span class="authors">Kelvin Luu and Csaba Tóth</span>. <span class="title">Geometric $(1+\varepsilon)$-Spanners with Few Crossings</span> <span class="track">[T1]</span></td>
    </tr>
    <tr class="session">
      <td>16:10 &mdash; 16:30</td>
      <td><span class="authors">Oswin Aichholzer, Joseph Dorfer, Peter Kramer, Christian Rieck and Birgit Vogtenhuber</span>. <span class="title">Structural Properties of Shortest Flip Sequences Between Plane Spanning Trees</span> <span class="track">[T1]</span></td>
    </tr>
    <tr class="special">
      <td><strong>16:45 &mdash; 17:00</strong></td>
      <td><strong>Closing Remarks & Award Ceremony, <span class="Location-info">Location: TBA</span></strong></td>
    </tr>
  </tbody>
</table>

<script>
// Function to scroll to specific sections
function scrollToSection(sectionId) {
  const element = document.getElementById(sectionId);
  if (element) {
    element.scrollIntoView({ 
      behavior: 'smooth', 
      block: 'start' 
    });
  }
}

// Function to check if a header has collapsible content
function checkForCollapsibleContent(header) {
  // Get the session time range from the header
  const headerTimeCell = header.querySelector('td:first-child');
  const headerTimeText = headerTimeCell.textContent.trim();
  
  // Extract start and end times (e.g., "09:00 &mdash; 12:00" -> start: "09:00", end: "12:00")
  // Handle both regular dash and HTML entity &mdash;
  let timeMatch = headerTimeText.match(/(\d{2}:\d{2})\s*[—–-]\s*(\d{2}:\d{2})/);
  
  // If no time match in first column, try second column
  if (!timeMatch) {
    const secondColumn = header.querySelector('td:nth-child(2)');
    if (secondColumn) {
      const secondColumnText = secondColumn.textContent.trim();
      timeMatch = secondColumnText.match(/(\d{2}:\d{2})\s*[—–-]\s*(\d{2}:\d{2})/);
    }
  }
  
  if (!timeMatch) {
    return false; // No time range found, can't be collapsible
  }
  
  const sessionStartTime = timeMatch[1];
  const sessionEndTime = timeMatch[2];
  
  // Check if there are any subsequent rows within the time range
  let nextRow = header.nextElementSibling;
  while (nextRow && nextRow.parentNode === header.parentNode) {
    // Stop if we hit another header
    if (nextRow.classList.contains('header')) break;
    
    // Check if this row belongs to the session
    const rowTimeCell = nextRow.querySelector('td:first-child');
    if (rowTimeCell) {
      const rowTimeText = rowTimeCell.textContent.trim();
      const rowTimeMatch = rowTimeText.match(/(\d{2}:\d{2})/);
      if (rowTimeMatch) {
        const rowStartTime = rowTimeMatch[1];
        // If row time is within session time range, this header has collapsible content
        if (rowStartTime >= sessionStartTime && rowStartTime < sessionEndTime) {
          return true;
        }
      }
    }
    nextRow = nextRow.nextElementSibling;
  }
  
  return false; // No collapsible content found
}

// Collapsible session functionality
document.addEventListener('DOMContentLoaded', function() {
  // Find ALL possible collapsible headers (including gdc)
  const collapsibleHeaders = document.querySelectorAll('tr.session.header, tr.poster.header, tr.phd-school.header, tr.gdc');
  
  collapsibleHeaders.forEach(header => {
    // Check if this header actually has collapsible content
    const hasCollapsibleContent = checkForCollapsibleContent(header);
    
    // Only add triangle and click functionality if there's collapsible content
    if (hasCollapsibleContent) {
      header.classList.add('collapsible');
    }
    
    // Add click functionality
    header.addEventListener('click', function() {
      const isCollapsed = this.classList.contains('collapsed');
      
      // Get the session time range from the header
      const headerTimeCell = this.querySelector('td:first-child');
      const headerTimeText = headerTimeCell.textContent.trim();

      
      // Extract start and end times (e.g., "09:00 &mdash; 12:00" -> start: "09:00", end: "12:00")
      // Handle both regular dash and HTML entity &mdash;
      let timeMatch = headerTimeText.match(/(\d{2}:\d{2})\s*[—–-]\s*(\d{2}:\d{2})/);
      
      // If no time match in first column, try second column
      if (!timeMatch) {
        const secondColumn = this.querySelector('td:nth-child(2)');
        if (secondColumn) {
          const secondColumnText = secondColumn.textContent.trim();

          timeMatch = secondColumnText.match(/(\d{2}:\d{2})\s*[—–-]\s*(\d{2}:\d{2})/);
        }
      }
      
      if (!timeMatch) {
        return; // Skip if no time range found
      }
      
      const sessionStartTime = timeMatch[1];
      const sessionEndTime = timeMatch[2];

      
      if (isCollapsed) {
        // Expand: show all rows that belong to this session
        this.classList.remove('collapsed');
        let nextRow = this.nextElementSibling;
        while (nextRow && nextRow.parentNode === this.parentNode) {
          // Stop if we hit another header
          if (nextRow.classList.contains('header')) break;
          
                     // Check if this row belongs to the session
           const rowTimeCell = nextRow.querySelector('td:first-child');
           if (rowTimeCell) {
             const rowTimeText = rowTimeCell.textContent.trim();
             const rowTimeMatch = rowTimeText.match(/(\d{2}:\d{2})/);
             if (rowTimeMatch) {
               const rowStartTime = rowTimeMatch[1];
               // If row time is within session time range, show it
               // Use < for end time to exclude rows that start exactly at the end time
               if (rowStartTime >= sessionStartTime && rowStartTime < sessionEndTime) {
                 nextRow.style.display = '';
               }
             }
           }
          nextRow = nextRow.nextElementSibling;
        }
      } else {
        // Collapse: hide all rows that belong to this session
        this.classList.add('collapsed');
        let nextRow = this.nextElementSibling;
        while (nextRow && nextRow.parentNode === this.parentNode) {
          // Stop if we hit another header
          if (nextRow.classList.contains('header')) break;
          
                     // Check if this row belongs to the session
           const rowTimeCell = nextRow.querySelector('td:first-child');
           if (rowTimeCell) {
             const rowTimeText = rowTimeCell.textContent.trim();
             const rowTimeMatch = rowTimeText.match(/(\d{2}:\d{2})/);
             if (rowTimeMatch) {
               const rowStartTime = rowTimeMatch[1];
               // If row time is within session time range, hide it
               // Use < for end time to exclude rows that start exactly at the end time
               if (rowStartTime >= sessionStartTime && rowStartTime < sessionEndTime) {
                 nextRow.style.display = 'none';
               }
             }
           }
          nextRow = nextRow.nextElementSibling;
        }
      }
    });
    
    // Add visual indicator that it's clickable
    header.style.cursor = 'pointer';
    header.title = 'Click to expand/collapse session';
  });
});

</script>

<script>
  const text = document.createTextNode(prefixText);
  linkContainer.appendChild(text);
  
  const jumpLink = document.createElement('a');
  jumpLink.href = `#${matchedCell.getAttribute('id')}`;

  if(showStartDate) {
    const startDate = new Date(matchedCell.getAttribute('schedule-link-start'))
    const dateDay = startDate.getDate().toString().padStart(2, '0');
    const dateMonth = (startDate.getMonth() + 1).toString().padStart(2, '0');
    const dateHour = startDate.getHours().toString().padStart(2, '0');
    const dateMinutes = startDate.getMinutes().toString().padStart(2, '0');
    jumpLink.textContent = `${matchedCell.getAttribute('schedule-link-text')} (Start: ${dateDay}.${dateMonth}, ${dateHour}:${dateMinutes})`;
  } else {
    jumpLink.textContent = `${matchedCell.getAttribute('schedule-link-text')}`;
  }

  
  
  linkContainer.appendChild(jumpLink);
}

  
function computeDynamicSessionLinks() {
  const now = new Date();
  
  const scheduleCells = document.querySelectorAll('.schedule-link');
  let lastMatchedCell = null;
  let nextMatchedCell = null;

  if (scheduleCells.length > 0) {
    nextMatchedCell = scheduleCells[0]
  }

  scheduleCells.forEach((cell, index) => {
    const scheduleTimeStart = new Date(cell.getAttribute('schedule-link-start'));         
    const scheduleTimeEnd = new Date(cell.getAttribute('schedule-link-end'));         
      
    if (scheduleTimeStart <= now) {
      if (now <= scheduleTimeEnd) {
        lastMatchedCell = cell;
      }      
      if (index < scheduleCells.length &mdash; 1) {
        nextMatchedCell = scheduleCells[index + 1];
      }
    }
  });

  if(lastMatchedCell) {
    fillDynamicSessionLinks(lastMatchedCell, 'Current Session: ', 'jump-current-session-link', false);
  }

  if(nextMatchedCell) {
    fillDynamicSessionLinks(nextMatchedCell, 'Next Session: ', 'jump-next-session-link', true);
  }
}

// computeDynamicSessionLinks();
</script>