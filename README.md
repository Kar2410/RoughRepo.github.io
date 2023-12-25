# RoughRepo.github.io

.m2/repository/mysql/mysql-connector-java/8.0.23/mysql-connector-java-8.0.23.jar

<myBirthdayMessage>Happy Birthday to me!</myBirthdayMessage>
    <friendBirthdayMessage>Happy Birthday to my friend!</friendBirthdayMessage>



    import { Component } from '@angular/core';

@Component({
  selector: 'app-reason-for-enrollment',
  templateUrl: './reasonforenrollment.component.html',
  styleUrls: ['./reasonforenrollment.component.css']
})
export class ReasonForEnrollmentComponent {

  myBirthday = new Date(1998, 11, 24); 
  friendBirthday = new Date(2000, 5, 30);

  myBirthdayMessage = "";
  friendBirthdayMessage = "";

  constructor() {
    this.myBirthdayMessage = // get translated message from XML
    this.friendBirthdayMessage = // get translated message 
  }

  onDateSelected(selectedDate: Date) {
    if(selectedDate.getMonth() === this.myBirthday.getMonth() && 
       selectedDate.getDate() === this.myBirthday.getDate()) {
         this.showMessage = this.myBirthdayMessage;
    } else if (selectedDate.getMonth() === this.friendBirthday.getMonth() &&
                selectedDate.getDate() === this.friendBirthday.getDate()) {
        this.showMessage = this.friendBirthdayMessage;
    }
  }

}




<input type="date" (change)="onDateSelected($event.target.value)">

<div>
  {{showMessage}}
</div





config

GEFConfig

SecurityConfig

Security ConfigDev

UserinfoOpaque TokenIntrospector

constants

Address Type

ContactType

controller

ContactsDocumentController

CustomerSummaryDocumentController

GEFReportController

HeartbeatController

exceptions

CustomerAccountNotFoundException

GlobalExceptionHandler

NoSuchCustomerAccountException

service

ContactsExcelService

Customer SummaryExcelService

DataService

ExcelWriterService

GEFReportService

GEFReportServicelmpl

utils

contactslist

customersummary

>db

> gef

Coordinates

PropertyConstantsUtils

WriterUtil

valueobjects

contacts

gef

Address

ContactAddress

CustomerAccount

CustomerNumber

CustomerSummary

JoinTFNPlanType

Policy

PolicyProductLine

Preferences

TollFreeNumber

Toll Free NumberDTO

bm_Jmd-contacts-document-generator-api
